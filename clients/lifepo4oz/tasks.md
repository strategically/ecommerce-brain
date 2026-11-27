# Tasks: LiFePO4 OZ

Only the call extractor adds tasks. Agents and Sam change status. Closed tasks older than 30 days move to `tasks-archive.md`.

Status: `proposed` -> `approved` -> `in-progress` -> `done` (or `waiting-on-client`, `dropped`)

## Active

## T-001 · Email proposed Google Ads plan to client
Owner: Sam · Status: proposed · Agreed: call 2026-11-20
Why: Agreed on the weekly call; client to review before the following week.
Context: [[brain/advertising/account-state]]
Done when: Plan emailed (draft only; Sam sends)

## T-002 · Implement click-to-call email capture with Woopra identify
Owner: Sam · Status: proposed · Agreed: call 2026-11-20
Why: 63 anonymous calls and 56 call-button clicks lost attribution.
Context: [[brain/site/page-inventory]]
Done when: Email gate live and firing Woopra identify

## T-003 · Build tracked shipping-status page for draft-order customers
Owner: Sam · Status: proposed · Agreed: call 2026-11-20
Why: Re-identify draft buyers via Zoho email links with wv_email.
Context: [[brain/site/page-inventory]]
Update 2026-11-27: Ernest suggested an order-tracking or invoice page could also link customer sessions across devices (call 2026-11-27).
Done when: Page live; submit triggers Woopra identify

## T-004 · Match anonymous calls to Zoho CRM and prepare offline conversion upload
Owner: Sam · Status: proposed · Agreed: call 2026-11-20
Why: Draft orders are 63% of revenue with 2% click-ID coverage.
Context: [[brain/advertising/account-state]]
Done when: Matched sales list ready; upload to Google Ads needs Sam approval (see escalations)

## T-006 · Recheck supplier data and correct conflicting cycle-life specs
Owner: Sam · Status: proposed · Agreed: call 2026-11-27
Why: Catalogue claims conflict; Ernest says cycle life depends on cell model (about 10,000 for MB56 and 314, about 8,000 for 280).
Context: [[brain/catalogue/enrichment-rules]]
Done when: product specs consistent with supplier data and the cell-model ratings.

## T-007 · Trial the proposed product-page layout
Owner: Sam · Status: proposed · Agreed: call 2026-11-27
Why: Ernest approved trying clearer specifications and support information.
Context: [[brain/site/page-inventory]]
Done when: layout live on the agreed pages with the test period noted.

## T-008 · Complete product-data import on the 500-metafield Matrixify plan, then cancel
Owner: Sam (assumed; owner not stated) · Status: proposed · Agreed: call 2026-11-27
Why: Plan chosen for the metafield import; cancel when the work is done.
Context: [[calls/2026-11-27]]
Done when: import complete and subscription cancelled.

## T-009 · Compare live-chat counts across weeks and conversions
Owner: Ernest · Status: proposed · Agreed: call 2026-11-27
Why: Chat volume dropped sharply after AI chat; need the real numbers.
Context: [[calls/2026-11-27]]
Done when: counts and conversions for recent weeks sent to Sam.

## T-010 · Provide Zoho quote figures
Owner: Ernest · Status: proposed · Agreed: call 2026-11-27
Why: Needed for the quote-to-order matching (see T-004).
Context: [[calls/2026-11-27]]
Done when: figures sent to Sam.

## T-011 · Check whether the off-grid system e-book can be a lead-generation resource
Owner: Agora Data Driven · Status: proposed · Agreed: call 2026-11-27
Why: Possible Meta lead-generation offer using free resources.
Context: [[calls/2026-11-27]]
Done when: Agora confirms whether it can be used.

## Waiting on client

## T-005 · Woopra to resend tracking instructions, tag link and call-event report
Owner: Ryan (Woopra) · Status: proposed · Agreed: call 2026-11-20
Why: Needed for the tracking build.
Context: [[brain/site/page-inventory]]
Done when: Items received by Sam

## Done (last 30 days)

_None yet._

<!-- Task format:
## T-001 · Title
Owner: <agent> · Status: proposed · Agreed: call YYYY-MM-DD
Why: one line
Context: [[brain/...]]
Done when: observable outcome
-->
