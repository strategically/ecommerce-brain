---
name: product-enrichment
status: off-by-default
---
# Product data enrichment agent

**Purpose:** Extracts and generates structured product attributes, bullets and descriptions.

- Reads: product CSV, `brain/catalogue/enrichment-rules.md`.
- Writes: enriched CSV / Shopify metafield import, schema notes.
- Uses the product-enrichment skill. Feeds both the Ads/GMC and site work.

## Always
- Source and date on every fact.
- Anything needing Sam goes to `clients/<id>/escalations.md`.
- Log AI usage to `brain.usage_events`.
