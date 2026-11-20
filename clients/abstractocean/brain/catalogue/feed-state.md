# Abstract Ocean: feed state

_Merchant Center and feed state as stated on calls, latest first within each block. Counts are as spoken and some conflict (see open-questions)._

## Latest known state (2026-11-09)
- Shopify feeds hold about 1,175 USA products, 227 Canadian and 163 French-Canadian products (call 2026-11-09).
- Merchant Center labels exclude low-margin items to focus spend on PPF and armour; low-margin collective products removed from ad feeds gradually (call 2026-09-28).
- Facebook and Meta catalog cleaned and low-ticket SKUs excluded (call 2026-08-03). Product mapping needs fixing to stop irrelevant creatives (call 2026-08-03).
- Google and Shopify connections: a second organisation holds Shopify, Merchant Center, Google Ads and Business Profile; do not disconnect, create new Merchant Centers or unlink Google Ads before Google advises (call 2026-11-09).
- Aggregate review snippets and free listings dropped from about 766 to about 348 valid listings, coinciding with the review provider switch to Junip; Pete to ticket Junip (call 2026-09-03).
- Mass disapprovals: about 438 of about 2,163 products temporarily not approved on 2026-09-09 and 2026-09-10 after HTTP 500 errors; approvals back near normal by 2026-09-14 (call 2026-09-14).

## Disapproval history
- 2026-08-10: 67 products flagged for image overlay (crop or auto-fix and resubmit), 13 vinyl products resubmitted, 3 products misclassified as vehicles (call 2026-08-10).
- 2026-07-27: Merchant Center reports 36 products outside the CSS quota (call 2026-07-27).
- 2026-07-20: about 14 to 18 products disapproved, none high priority; stable (call 2026-07-20).
- 2026-07-06: about 11% of products unavailable for ads, down from about 16% earlier that morning; new robots.txt live at 2am (call 2026-07-06).
- 2026-06-29: US disapprovals improved from about 100 to 44; cause thought to be bot controls, robots.txt and rate limiting (call 2026-06-29).
- 2026-06-22: 500 and 503 errors; reasons include image too small, promotional overlay, missing shipping information and "product page unavailable"; many reference variant URLs; affected count about 140 to 150 earlier, about 17 at the call (call 2026-06-22).
- 2026-06-15: not-approved products peaked at 298 of 917 (about 30%) on 29 March; then about 44 to 51; missing GTINs and barcodes flagged (call 2026-06-15).
- 2026-04-13 and 2026-04-23: intermittent "product page unavailable" and 500 errors on US product pages; 30 to 40 re-review requests; cause unconfirmed (calls 2026-04-13, 2026-04-23). One product showed a missing aggregateReview field despite visible reviews (call 2026-04-23).
- 2025-04-30: some products disapproved for text on images; Pete says old and not significant (call 2025-04-30).

## Root-cause hypotheses over time (not confirmed)
- Clarity, firewall and bot rules (2026-06-15); 503 errors on checkout and cart assets during page load (2026-06-22); robots.txt, bot controls and rate limiting (2026-06-29); new robots.txt with explicit Google rules (2026-07-06); Cloudflare proxy blocking verification, fix by changing the www record to DNS-only (2026-07-13); Merchant Center stable afterwards (2026-07-20); bot protection removed inflating sessions (2026-07-27). The robots.txt file also blocks a crawler used by OpenAI (call 2026-07-20).

## Feed fixes and actions on record
- Fill missing GTINs and barcodes, using AI auto-fill, and re-upload the corrected feed (call 2026-06-15).
- Strip secondary geo-locations from the Google feed to reduce product count (call 2026-06-22).
- Wholesale SKUs unlisted to stop irrelevant Google indexing (call 2026-07-27).
- Merchant Center brand page to be completed to use new features (such as Business Agent, US only) (call 2026-04-27).
- Daily morning re-request of Merchant Center review (call 2026-06-22); tracking sheet for disapproved counts (call 2026-06-15).
- Uploads: 400 low-click products (including variants) uploaded 2026-02-21 with label four (call 2026-02-23); 470 products optimised and uploaded the week of 2026-04-27 with condition corrected to new (call 2026-04-27).
- Supplemental feed can override existing imagery; an export with a single 1x1 image would remove three existing images (call 2025-12-08).
- Product highlights and attribute drafts prepared for Merchant Center; Merchant Center issues noted: incorrect adult flag, age group, colours and material (call 2025-12-05).
- Review data was still served from Target Bay in 2025-10 while Redo's Google integration was ready (call 2025-10-17).
