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

## T-006 · Recheck supplier data and correct inconsistent product specs and cycle-life claims
Owner: Sam · Status: proposed · Agreed: call 2026-11-27
Why: Catalogue has conflicting specs; Ernest clarified cycle life by cell model.
Context: [[brain/catalogue/enrichment-rules]]
Done when: Corrected specs ready for Ernest to check; live product changes need Sam approval.

## T-007 · Roll out accessory product-page layout test
Owner: Sam · Status: proposed · Agreed: call 2026-11-27
Why: Ernest approved trying clearer specs and support information.
Context: [[brain/site/page-inventory]]
Done when: Test layout live on agreed accessory pages and compared against current pages.

## T-008 · Find and fix cause of the stacked Black Friday discount, then assess
Owner: Sam · Status: proposed · Agreed: call 2026-11-27
Why: 25% promo applied on top of an existing 25% discount, selling some orders at about 50% off.
Context: [[brain/site/page-inventory]]
Done when: Cause fixed and effect on sales and margin reviewed.


## Waiting on client

## T-005 · Woopra to resend tracking instructions, tag link and call-event report
Owner: Ryan (Woopra) · Status: proposed · Agreed: call 2026-11-20
Why: Needed for the tracking build.
Context: [[brain/site/page-inventory]]
Done when: Items received by Sam

## T-009 · Compare chat counts across weeks and check conversions
Owner: Ernest (client) · Status: waiting-on-client · Agreed: call 2026-11-27
Why: Chat volume fell sharply; need to know whether any chats converted.
Context: [[calls/2026-11-27]]
Done when: Counts and conversions sent to Sam.

## T-010 · Provide Zoho quote figures
Owner: Ernest (client) · Status: waiting-on-client · Agreed: call 2026-11-27
Why: Needed for the quote-to-sale picture.
Context: [[calls/2026-11-27]]
Done when: Figures received.

## T-011 · Forward email about possible theme upgrade
Owner: Ernest (client) · Status: waiting-on-client · Agreed: call 2026-11-27
Why: Sam to review the upgrade.
Context: [[calls/2026-11-27]]
Done when: Email received.

## T-012 · Check whether off-grid e-book can be used as a lead-generation resource
Owner: Agora Data Driven (vendor) · Status: waiting-on-client · Agreed: call 2026-11-27
Why: Possible Meta lead offer using free resources.
Context: [[calls/2026-11-27]]
Done when: Answer received.


## Done (last 30 days)

_None yet._

<!-- Task format:
## T-001 · Title
Owner: <agent> · Status: proposed · Agreed: call YYYY-MM-DD
Why: one line
Context: [[brain/...]]
Done when: observable outcome
-->
