# Tasks: Everything Truck Parts

Only the call extractor adds tasks. Agents and Sam change status. Closed tasks older than 30 days move to `tasks-archive.md`.

Status: `proposed` -> `approved` -> `in-progress` -> `done` (or `waiting-on-client`, `dropped`)

## Active

## T-001 · Launch Silverado filter-kit campaign with hidden SKU and component details
Owner: Sam · Status: proposed · Agreed: call 2026-11-24
Why: Kits launch at current pricing to test demand without exposing component data.
Context: [[brain/site/page-inventory]]
Done when: Silverado kit pages and campaign live.

## T-002 · Kit page fixes: pills, chassis/year wording, fitment table, volume pricing, replacement intervals
Owner: Sam · Status: proposed · Agreed: call 2026-11-24
Why: Revert engine selector to pills with better styling; larger chassis and year wording; fitment table limited to selected chassis engines; volume pricing off kit pages only; add replacement intervals.
Context: [[brain/site/page-inventory]]
Done when: John approves the updated kit pages.

## T-003 · Build kit-SKU to component-filter lookup by brand for fulfilment
Owner: Sam · Status: proposed · Agreed: call 2026-11-24
Why: Fulfilment needs component filters per kit; Fleetguard and Baldwin/WIX/Donaldson go to different recipients.
Context: [[brain/catalogue/enrichment-rules]]
Done when: Lookup delivered to John.

## T-004 · Send John the list of missing filter products
Owner: Sam · Status: proposed · Agreed: call 2026-11-24
Why: Silverado 1500 2019-2026 lacked a kit though WIX had three filters listed.
Context: [[brain/catalogue/feed-state]]
Done when: List emailed (by Sam himself).

## T-005 · Stop marketing shocks and struts category
Owner: Sam · Status: proposed · Agreed: call 2026-11-24
Why: Return figures discussed were exceptionally poor. Sam applies the change in the ad account himself (Stage 1).
Context: [[brain/advertising/account-state]]
Done when: Category excluded from paid campaigns.

## Waiting on client

## T-006 · Add missing filter products and update filter-page draft
Owner: John (client) · Status: waiting-on-client · Agreed: call 2026-11-24
Why: Follows T-004; draft must reflect engine selection and volume pricing changes.
Context: [[brain/catalogue/feed-state]]
Done when: Products added and draft updated.

## Done (last 30 days)

_None yet._

<!-- Task format:
## T-001 · Title
Owner: <agent> · Status: proposed · Agreed: call YYYY-MM-DD
Why: one line
Context: [[brain/...]]
Done when: observable outcome
-->
