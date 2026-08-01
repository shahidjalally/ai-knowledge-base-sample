# AI Knowledge Base Samples

This repository contains customer-support knowledge-base CSV samples:

- `ai-knowledge-base-sample.csv`: a Google Sheets-compatible knowledge base derived from `Zain Bike Center Knowledge.docx`, with broad English and Roman Urdu question coverage, source-grounded answers, and anti-hallucination escalation rules.
- `black-x-original-knowledge-base.csv`: 3,000 English question variants covering 89 support intents for Black x Original, a Pakistani ecommerce clothing brand.

The Zain Bike Center CSV keeps every answer grounded in the supplied document. It explicitly identifies unavailable, conflicting, current-stock, live-order, and account-specific information instead of guessing. Before production use, the business should verify payment-account details, prices, inventory, delivery terms, and policies, because the source document is not a live system.

The Black x Original file preserves the original CSV schema. Its answers distinguish verified store facts from details that must be checked on the live store, checkout, product page, or applicable policy. This prevents the chatbot from inventing prices, stock, delivery promises, contact details, or return terms when live information changes. Product, policy, and order-specific answers should be synchronized with `https://blxck.pk/` before production deployment.
