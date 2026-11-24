# Tasks: Everything Truck Parts

Only the call extractor adds tasks. Agents and Sam change status. Closed tasks older than 30 days move to `tasks-archive.md`.

Status: `proposed` -> `approved` -> `in-progress` -> `done` (or `waiting-on-client`, `dropped`)

## Active

## T-001 · Remove app volume-discount block from kit pages
Owner: Sam · Status: proposed · Agreed: call 2026-11-24
Why: the "Get more, save more" app block does not change the SKU; the built-in 6+ tier already exists.
Context: [[brain/site/page-inventory.md]]
Done when: kit page shows no app block (Item 1-6 pickers); built-in buy 6+ save 5% stays; engine pill styling and label size checked by eye; John approves.

## T-002 · Limit copy, FAQ and fitment box to the selected chassis
Owner: Sam · Status: proposed · Agreed: call 2026-11-24
Why: pills are already chassis-only, but FAQ, intro copy and the "No Fitment Data" box still reference other years and engines.
Context: [[brain/catalogue/enrichment-rules.md]]
Done when: FAQ example, "Your Silverado 1500" text and engine list match the chassis; fitment box omitted on kits; own replacement-interval wording (no "owner's manual takes precedence").

## T-003 · Hide component part numbers and brand SKUs on kit pages
Owner: Sam · Status: proposed · Agreed: call 2026-11-24
Why: stop competitors and customers rebuilding the kit from individual parts.
Context: [[brain/decisions.md]]
Done when: kit copy and images show no part codes; kit SKU not shown in the customer cart.

## T-004 · Exclude kits from the volume-discount app
Owner: John · Status: proposed · Agreed: call 2026-11-24
Why: the app must stay on other filter pages but not on kits.
Context: [[brain/site/page-inventory.md]]
Done when: kit pages no longer render the app; other filter pages unchanged.

## T-005 · Add missing Silverado 2019-2026 parts
Owner: Sam, then John · Status: proposed · Agreed: call 2026-11-24
Why: kits for 2019-2026 are blocked until WIX air and cabin parts (about five products) exist in the store.
Context: [[brain/catalogue/feed-state.md]]
Done when: Sam emails the product list and the light-duty WIX air part is confirmed; John adds them; kits build.

## T-006 · Build kit SKU to component lookup spreadsheet
Owner: Sam · Status: proposed · Agreed: call 2026-11-24
Why: replaces the metafield and bundle-app plan so Diane can send the warehouse part numbers per order.
Context: [[brain/business/profile.md]]
Done when: a sheet split by brand (Baldwin, WIX, Donaldson to one warehouse contact; Fleetguard separately) is with John and Diane.

## T-007 · Launch Silverado campaign, then RAM, then F-150
Owner: Sam · Status: proposed · Agreed: call 2026-11-24
Why: pages are close; ads go live once pages are signed off.
Context: [[brain/advertising/account-state.md]]
Done when: Silverado campaign live after sign-off; RAM and F-150 follow in that order.

## T-008 · Remove high-return shocks and Rhino from promotion
Owner: Sam · Status: proposed · Agreed: call 2026-11-24
Why: shocks and struts (Bilstein, Fox, Eibach) returned at very high rates; Rhino drop-ship orders are auto-cancelled.
Context: [[brain/advertising/change-log.md]]
Done when: those items are excluded from feeds and campaigns and John confirms.

## T-009 · Build ETP returns and financial model
Owner: Sam · Status: proposed · Agreed: call 2026-11-24
Why: set category ROAS targets by returns and margin; decide what to sell and not sell.
Context: [[brain/business/unit-economics.md]]
Done when: target sheet with margin and Shopify returns tabs exists and feeds the finance agent.

## T-010 · Investigate organic traffic drop
Owner: Sam · Status: proposed · Agreed: call 2026-11-24
Why: organic down about 20% in the period; also flagged 2026-11-10.
Context: [[brain/business/open-questions.md]]
Done when: cause identified and recommendation raised.

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
