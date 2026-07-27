# AI Knowledge Base Samples

This repository contains customer-support knowledge-base CSV samples:

- `ai-knowledge-base-sample.csv`: the original SRLINES sample.
- `black-x-original-knowledge-base.csv`: 3,000 English question variants covering 89 support intents for Black x Original, a Pakistani ecommerce clothing brand.

The Black x Original file preserves the original CSV schema. Its answers distinguish verified store facts from details that must be checked on the live store, checkout, product page, or applicable policy. This prevents the chatbot from inventing prices, stock, delivery promises, contact details, or return terms when live information changes. Product, policy, and order-specific answers should be synchronized with `https://blxck.pk/` before production deployment.
