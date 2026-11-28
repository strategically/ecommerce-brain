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
Done when: Page live; submit triggers Woopra identify

## T-004 · Match anonymous calls to Zoho CRM and prepare offline conversion upload
Owner: Sam · Status: proposed · Agreed: call 2026-11-20
Why: Draft orders are 63% of revenue with 2% click-ID coverage.
Context: [[brain/advertising/account-state]]
Done when: Matched sales list ready; upload to Google Ads needs Sam approval (see escalations)

## T-006 · Send Ernest the list of products needing accurate specifications
Owner: Sam · Status: proposed · Agreed: call 2026-11-27
Why: Catalogue has conflicting specs, e.g. cycle life.
Context: [[brain/catalogue/enrichment-rules]]
Done when: List emailed to Ernest (draft only; Sam sends)

## T-007 · Apply accessory product data patch and recheck supplier specs
Owner: Sam · Status: proposed · Agreed: call 2026-11-27
Why: Ernest approved the fix on the call.
Context: [[brain/catalogue/enrichment-rules]]
Done when: Patch applied; specs consistent with supplier data

## T-008 · Build and test new accessory product-page layout
Owner: Sam · Status: proposed · Agreed: call 2026-11-27
Why: Ernest approved testing the layout.
Context: [[brain/site/page-inventory]]
Done when: Layout live and test running

## Waiting on client

## T-005 · Woopra to resend tracking instructions, tag link and call-event report
Owner: Ryan (Woopra) · Status: proposed · Agreed: call 2026-11-20
Why: Needed for the tracking build.
Context: [[brain/site/page-inventory]]
Done when: Items received by Sam

## T-009 · Ask supplier for specification sheets
Owner: Ernest (client) · Status: waiting-on-client · Agreed: call 2026-11-27
Why: Needed to correct product specs.
Context: [[brain/catalogue/enrichment-rules]]
Done when: Sheets received by Sam

## T-010 · Compare live-chat counts and conversions across weeks
Owner: Ernest (client) · Status: waiting-on-client · Agreed: call 2026-11-27
Why: Chat volume fell and none converted last week.
Context: [[brain/site/page-inventory]]
Done when: Counts sent to Sam

## T-011 · Provide Zoho quote figures when available
Owner: Ernest (client) · Status: waiting-on-client · Agreed: call 2026-11-27
Why: Sam requested them for analysis.
Context: [[brain/advertising/account-state]]
Done when: Figures received

## T-012 · Forward theme upgrade email
Owner: Ernest (client) · Status: waiting-on-client · Agreed: call 2026-11-27
Why: Possible theme upgrade.
Context: [[brain/site/page-inventory]]
Done when: Email received by Sam

## T-013 · Send copycat-site details (via Fiona) to Sam and Agora Data Driven
Owner: Ernest (client) · Status: waiting-on-client · Agreed: call 2026-11-27
Why: Two sites allegedly copied the website.
Context: [[brain/site/page-inventory]]
Done when: Details received

## Done (last 30 days)

_None yet._

<!-- Task format:
## T-001 · Title
Owner: <agent> · Status: proposed · Agreed: call YYYY-MM-DD
Why: one line
Context: [[brain/...]]
Done when: observable outcome
-->
