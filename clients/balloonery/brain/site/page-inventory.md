# Balloonery: pages and CRO tests

_Facts from calls only. Traffic and conversion numbers live in the database._

## Geolocation, redirects and US structure
- Theme-level redirects removed to avoid redirect loops; the Geos app handles the visitor country pop-up (call 2026-01-15). A US to Canada to US redirect chain was seen afterwards and not reproduced (call 2026-01-15).
- Intermittent Google crawler issue to be addressed through the geolocation setup (call 2026-03-12); alternative apps, including Orb, to be evaluated if not resolved (call 2026-03-26).
- US structure options: Shopify Markets merge, separate US store, Shopify Plus; undecided (call 2026-03-26). Shopify Markets filters by country not region (call 2026-11-05).
- Shawn suspected a traffic drop related to the Markets rollout; checked in the technical audit (call 2025-12-09).

## Location pages and delivery widget
- Location pages record zip-code checks in a spreadsheet and collect email from visitors outside the zone (call 2026-03-12). The cart page takes a zip code and logs it with an email for visitors outside the region (call 2026-05-07).
- Lovable-built zip-code tool kept as a self-contained iframe in the new theme for the location page (call 2026-05-21).
- Partner pages converted to location landing pages with local H1 tags; partner-branded pages persist a partner slug in a cookie and attribute the original partner on the order (call 2026-07-02). Partner button piloted on the New York partner website (call 2026-07-02).
- New location landing page template built by Sam and signed off by Shawn, wording open to edits (call 2026-11-05). Houston page approved to launch after checks (call 2026-11-19).
- Decor orders outside served zip codes can check out at a fixed delivery price as a fallback only; where a partner serves the zip code the normal fee applies (call 2026-11-05).
- ZIP selector failed for one test postcode and the mobile selector is visually cut off, both to fix before launch (call 2026-11-19).

## Collections and navigation
- Collections are sub-level filter pages; they are not indexed when the filter sits after a question mark in the URL (call 2026-03-12). Proposed block of about five to ten subfolder links at the top of the birthday collection (call 2026-03-12). Existing theme kept; top-level collections link to subcollections (call 2026-03-12).
- Smart collections with tag-based rules (call 2026-03-26). Collections link back to parent collections: one or two (call 2026-05-07), now at least two or three (call 2026-05-21).
- Collection copy rewritten after feedback that the first version read as negative; brand voice document being built (call 2026-05-21).
- Collection pages: occasion-specific filters, indexable collections, larger images, less whitespace, four-wide cards where possible (call 2026-11-19).

## Product pages and templates
- Attribute table of contents and schema on the product page planned (call 2026-05-07). Customise option shows upsell products linked to the gender attribute (call 2026-05-07).
- Product page template, no bullets in copy, search tags removed from the page; theme changes built in parallel on a new theme and merged, not edited live (call 2026-05-21). Minimal customisation of the existing theme (call 2026-05-07).
- Product pages need smaller ZIP selectors and further design work; Live Product Options stay dynamically controlled without theme-level conflicts (call 2026-11-19).
- Contact flow: contact form buried under a Contact Us button at the bottom of pages and chat is the primary flow (call 2026-10-07). Contact flow primary on the decor side with a clear first step rather than a long form (call 2026-10-07). Version 2 product page with form is an option (call 2026-10-07).

## Forms, chat and email
- Contact page email link changed to a click-to-reveal button tracked in GTM (call 2026-09-24).
- Native Shopify live chat is pushy and asks for a sign-in; rebuild so it opens by default and evaluate a new tool (call 2026-10-07; livechat.com under evaluation, call 2026-09-24).
- Anniversary email: social links removed, unsubscribe at the top, single call-to-action to a custom collection page (call 2026-10-22). Upsells in confirmation and delivery emails; standalone confirmation calendar planned (call 2026-09-24).
- Review request sent after delivery; review platform (Judge.me suggested) to be set up (call 2026-11-05).
- Lead form and call tracking: contact form to be put up and lead form submissions attributed (call 2026-08-12).
