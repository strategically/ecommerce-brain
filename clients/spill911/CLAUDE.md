# Spill911

- id: `spill911` · type: retainer · DB schema: `spill911` (created when first data is loaded)
- Call cadence: bi-weekly Wednesday call "PPC & SEO" with Bill (calls 2025-05-14 to 2026-10-14) plus one-to-one sessions with John (calls 2025-04-21, 2025-05-15, 2025-06-27, 2025-09-30, 2025-10-30, 2026-11-11); some sessions shared with Everything Truck Parts
- Contacts and roles: John, day-to-day contact (Shopify, imports, theme access, Rejoiner, government leads, hiring); Bill (William), vendors, pricing, freight data, approves campaign budgets (call 2026-02-04); Sam Franklin, Strategically account lead (PPC, enrichment, feed, schema, tracking, page design); Mustafa, Strategically (2025 PPC calls)
- Retainer / AI budget (CFO sets): TBC. Not stated on any call
- Guardrails and do-not-touch (stated on calls):
  - Take a full Shopify export (Matrixify) as backup before bulk changes (2025-12-11)
  - Keep SKU and part number unchanged for order matching when titles change (2025-12-11)
  - Change the Merchant Center shipping weight cap slowly and carefully (2026-01-07)
  - Bill approves campaign budgets after Sam's update (2026-02-04)
  - Do not cancel the Shopify tag app until server-side tracking is fully live (2026-04-01)
  - GSA-related advertising is subject to the contracting officer's constraints (2026-04-01)
  - John approves sample enrichment outputs; Bill signs off the Vestil import test (2026-04-29, 2026-10-14)
  - Test enrichment on the Attributes theme (duplicate of live) before going live (2026-05-13)
  - Vestil template only for products with required data and pricing; newly added products stay draft until Bill prices them (2026-10-30)
  - MAP-priced brands (for example Justrite, Eagle) limit pricing freedom (2026-08-19)
  - Judge performance on cleaned data, not bot-inflated Shopify analytics (2026-09-16)
  - Stage 1 (to 15 Dec 2026): agents recommend, Sam approves and applies

## Summary (backfilled from 40 calls, 2025-04-21 to 2026-11-11)
Shopify store selling spill containment, absorbents, material handling and storage to industry and government, with large offline and government sales outside Shopify. Work ran in phases: PPC waste pruning and breadcrumb fixes (spring 2025); a pause on PPC in favour of product data enrichment starting with Peabody (mid 2025); attribute schema, Matrixify imports and 5,000-title Merchant Center supplemental feed (late 2025); brand and subcategory Shopping, then exact-match and part-number SKAG search (2026); freight, RFQ and shipping-integration experiments (spring 2026); Vestil data import and page template, Bing as a separate channel, and quote follow-up tooling (autumn 2026). Main unresolved items: gross margin, ROAS and MER definitions, true Google profitability, bot-inflated analytics and attribution of offline and AI-referred orders. See `brain/business/open-questions.md`.

Read `tasks.md` next, then `brain/`.

## Index of brain files
- `brain/business/profile.md`: what the business sells, vendors, channels, team, tools
- `brain/business/unit-economics.md`: margin status, freight and shipping economics, ROAS rules, tool costs
- `brain/business/targets.md`: revenue, ROAS, validation thresholds, budget settings
- `brain/business/open-questions.md`: conflicting figures and items to confirm
- `brain/advertising/account-state.md`: current Google and Bing structure and strategy (as of 2026-11-11)
- `brain/advertising/change-log.md`: dated advertising changes, newest first
- `brain/catalogue/enrichment-rules.md`: attribute schema, titles, import method, Vestil import
- `brain/catalogue/feed-state.md`: Merchant Center and Bing feed state, indexing, schema
- `brain/site/page-inventory.md`: collections, hub pages, templates, forms, theme rules
- `brain/decisions.md`: dated decisions with supersessions
- `brain/timeline.md`: monthly timeline
- `calls/`: 40 call notes (emails redacted to first names)
- `tasks.md`, `escalations.md`: scaffold, no tasks created from history
