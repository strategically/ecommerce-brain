# Tasks: Spill911

Only the call extractor adds tasks. Agents and Sam change status. Closed tasks older than 30 days move to `tasks-archive.md`.

Status: `proposed` -> `approved` -> `in-progress` -> `done` (or `waiting-on-client`, `dropped`)

## Active

## T-001 · Add brand names to product titles and apply taxonomy
Owner: Sam · Status: proposed · Agreed: call 2026-11-25
Why: Agreed on the call; improves product discovery by search engines and AI systems.
Context: [[brain/catalogue/enrichment-rules]]
Done when: the roughly 16,000-17,000 products without a brand in the title have it added, with a space between brand and product name, and a product taxonomy is applied.

## T-002 · Staged product data improvement
Owner: Sam · Status: proposed · Agreed: call 2026-11-25
Why: Agreed to improve data in stages rather than wait for perfection.
Context: [[brain/catalogue/enrichment-rules]]
Done when: core fields (dimensions, weight, materials, safety information) are standardised first, then product- and brand-specific information is added and shown in the storefront and product schema.

## T-003 · Request a Quote app on product-page template
Owner: Sam · Status: proposed · Agreed: call 2026-11-25
Why: Oversized and complex products need a clear quote route and freight text.
Context: [[brain/catalogue/enrichment-rules]]
Done when: the Request a Quote app works with the template, a clear quote button and freight text show for oversized products, and Vestil product pages missing the correct template are identified.

## T-004 · Offline-sales data layer
Owner: Sam (with John) · Status: proposed · Agreed: call 2026-11-25
Why: Offline sales are not in analytics; reconcile with other business data.
Context: [[brain/business/open-questions]]
Done when: the offline sales spreadsheet is linked to the AI system and reconciled with the other data.

## Waiting on client

## T-005 · Customer records and CRM structure
Owner: John and Bill · Status: waiting-on-client · Agreed: call 2026-11-25
Why: Decide how customer records and business knowledge (email, Shopify, other systems) are stored to support customer communication and later AI work.
Context: [[brain/business/profile]]
Done when: John and Bill have decided on a structured database or CRM approach (John to review HubSpot and other options in December).

## T-006 · Automated follow-up for Vestil downloads
Owner: John · Status: waiting-on-client · Agreed: call 2026-11-25
Why: Support-staff follow-ups have been inconsistent.
Context: [[brain/site/page-inventory]]
Done when: an automated flow (Shopify, Claude or another system) follows up download leads until they are ready for a phone call.

## Done (last 30 days)

_None yet._

<!-- Task format:
## T-001 · Title
Owner: <agent> · Status: proposed · Agreed: call YYYY-MM-DD
Why: one line
Context: [[brain/...]]
Done when: observable outcome
-->
