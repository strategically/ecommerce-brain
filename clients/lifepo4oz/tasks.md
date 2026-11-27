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

## T-006 · Recheck supplier data and correct inconsistent product specifications
Owner: Sam · Status: proposed · Agreed: call 2026-11-27
Why: Conflicting cycle-life claims found across the catalogue; Ernest gave cycle life by cell model.
Context: [[brain/catalogue/enrichment-rules]]
Done when: Specs consistent with supplier data and the cell-model ratings; changes proposed for approval

## Waiting on client

## T-005 · Woopra to resend tracking instructions, tag link and call-event report
Owner: Ryan (Woopra) · Status: proposed · Agreed: call 2026-11-20
Why: Needed for the tracking build.
Context: [[brain/site/page-inventory]]
Done when: Items received by Sam

## T-007 · Ernest to compare live-chat counts and conversions across date ranges
Owner: Ernest (client) · Status: waiting-on-client · Agreed: call 2026-11-27
Why: Chat volume dropped sharply after the AI chat system; need to see whether chats converted.
Context: [[brain/site/page-inventory]]
Done when: Ernest supplies chat counts and conversions for prior ranges

## T-008 · Ernest to provide Zoho quote figures
Owner: Ernest (client) · Status: waiting-on-client · Agreed: call 2026-11-27
Why: Sam asked for quote figures; Ernest said he might be able to get them.
Context: [[brain/business/open-questions]]
Done when: Figures received

## Done (last 30 days)

_None yet._

<!-- Task format:
## T-001 · Title
Owner: <agent> · Status: proposed · Agreed: call YYYY-MM-DD
Why: one line
Context: [[brain/...]]
Done when: observable outcome
-->
