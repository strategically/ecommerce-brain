# Tasks: LiFePO4 OZ

Only the call extractor adds tasks. Agents and Sam change status. Closed tasks older than 30 days move to `tasks-archive.md`.

Status: `proposed` -> `approved` -> `in-progress` -> `done` (or `waiting-on-client`, `dropped`)

## Active

## T-006 · Send Ernest the list of products needing accurate specifications
Owner: Sam · Status: proposed · Agreed: call 2026-11-27
Why: Catalogue specs inconsistent, including cycle life.
Context: [[brain/catalogue/enrichment-rules]]
Done when: List sent


## T-007 · Ask supplier for specification sheets
Owner: Ernest (client) · Status: proposed · Agreed: call 2026-11-27
Why: Needed to correct product data.
Context: [[brain/catalogue/enrichment-rules]]
Done when: Sheets received by Sam


## T-008 · Fix incorrect accessory product data with uploaded patch
Owner: Sam · Status: proposed · Agreed: call 2026-11-27
Why: Ernest approved the patch.
Context: [[brain/catalogue/enrichment-rules]]
Done when: Patch applied and checked


## T-009 · Test proposed accessory product-page layout
Owner: Sam · Status: proposed · Agreed: call 2026-11-27
Why: Ernest approved trying concise specs, support and warranty layout.
Context: [[brain/site/page-inventory]]
Done when: Test live with result read-out


## T-010 · Review chat records and conversions across weeks
Owner: Ernest (client) · Status: proposed · Agreed: call 2026-11-27
Why: Chats fell from about 12 to 1 a week, none converting.
Context: [[calls/2026-11-27]]
Done when: Counts and conversions shared with Sam


## T-011 · Provide Zoho quote figures
Owner: Ernest (client) · Status: proposed · Agreed: call 2026-11-27
Why: Needed for offline conversion matching.
Context: [[calls/2026-11-20]]
Done when: Figures received

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
