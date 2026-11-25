# Tasks: Everything Truck Parts

Only the call extractor adds tasks. Agents and Sam change status. Closed tasks older than 30 days move to `tasks-archive.md`.

Status: `proposed` -> `approved` -> `in-progress` -> `done` (or `waiting-on-client`, `dropped`)

## Active

## T-001 · Get Silverado filter-kit campaign live with component details hidden
Owner: Sam · Status: proposed · Agreed: call 2026-11-24
Why: Kits launch without SKU or component details at current pricing to test demand and protect product information.
Context: [[brain/site/page-inventory]], [[brain/catalogue/enrichment-rules]]
Done when: Silverado kit pages and campaign are live with SKUs and component details not shown. Due date not stated.

## T-002 · Build kit SKU to component filter lookup for fulfilment
Owner: Sam · Status: proposed · Agreed: call 2026-11-24
Why: Fulfilment needs component filters per kit SKU, separated by brand.
Context: [[brain/catalogue/enrichment-rules]]
Done when: A lookup document or database maps each kit SKU to its components by brand and John has it. Due date not stated.

## T-003 · Send John the list of missing filter products; John to add them
Owner: Sam (send list), John (add products) · Status: proposed · Agreed: call 2026-11-24
Why: Kit pages need all component products present in the store.
Context: [[brain/catalogue/feed-state]]
Done when: List sent and John has added the products. Due date not stated.

## T-004 · Update filter-page draft: engine pills, volume purchasing, larger chassis and year wording
Owner: Sam · Status: proposed · Agreed: call 2026-11-24
Why: Agreed changes from the review of the updated filter-kit page.
Context: [[brain/site/page-inventory]]
Done when: Draft shows engine-selection pills, volume-purchasing change and larger chassis and year text. Due date not stated.

## T-005 · Check volume-pricing behaviour on filter pages
Owner: Sam · Status: proposed · Agreed: call 2026-11-24
Why: Volume pricing is triggered by brand and matters for the other filter pages.
Context: [[brain/site/page-inventory]]
Done when: Behaviour confirmed on the filter pages. Due date not stated.

## T-006 · Remove shocks and struts, and Rhino, from marketing
Owner: Sam · Status: proposed · Agreed: call 2026-11-24
Why: Poor return figures on shocks and struts; Rhino cancels out-of-stock drop-ship orders.
Context: [[brain/advertising/change-log]]
Done when: Both are excluded from paid campaigns and the marketing feed. Due date not stated; John approves feed and product removals per earlier guardrails.

## Waiting on client

_None yet._

## Done (last 30 days)

_None yet._

<!-- Task format:
## T-001 · Title
Owner: <agent> · Status: proposed · Agreed: call YYYY-MM-DD
Why: one line
Context: [[brain/...]]
Done when: observable outcome
-->
