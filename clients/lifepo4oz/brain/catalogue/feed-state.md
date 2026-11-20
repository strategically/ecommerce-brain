# LiFePO4 OZ: feed state

_Facts from calls only. Counts are as spoken and may be rough._

## Merchant Center
- Feed is a TSV that overlays Shopify data, matched on product ID (call 2026-06-04). Earlier the feed came via a separate app and now syncs differently (call 2025-09-18).
- Disapprovals: one robots.txt change blocked variant pages and disapproved many shopping products (call 2026-05-21); 1 to 169 after a Shopify outage returned errors on 3 June (call 2026-06-04); about 107 products impacted by 404/500 errors, review takes about 3 days (call 2026-09-10). Sam believes products were also changed by accident (call 2026-09-24).
- Fix priority: Merchant Center disapprovals top priority (call 2026-09-10). Robots.txt edits limited to technical SEO (Sam recommended; not confirmed) (call 2026-05-21).
- Valid merchant listings about 80 now, previously 96-97, rebounding (call 2026-04-16; partly unclear).
- Optimisation gains: about 17% more merchant clicks and CPC down from about $0.80-0.90 to about $0.65 (Ernest, call 2026-01-22).
- Open items: move custom labels into the feed (call 2025-09-18); delivery times under 10 days (call 2025-12-04); reviews programme eligibility (call 2025-12-11); in-stock flags and Shopify cost data merge (call 2025-12-11); whether variants (with/without display) report separately (call 2026-01-22).

## Product data
- Stock quantities: test using a placeholder (e.g. 100) rather than 0; check effect on Merchant Center (call 2026-02-19).
- Metaobjects and product metafields created for every product (battery chemistry, capacity, lifecycle, depth of discharge, installation type, warranty, BMS certifications, panel wattage) (call 2026-04-16). Lifecycle was wrongly set to five on some products (call 2026-04-16).
- Specs: capacity in kWh primary, amp-hours secondary (call 2026-04-30); kit data to show inverter kW and solar kW, use-case and "what's included" attributes (call 2026-05-07). System voltage (12/24/48) and usable kWh to be added to off-grid pages (call 2026-06-11). "Compatible with JK BMS" copy to become "JK BMS included" (call 2026-10-22).
- Product schema error: off-grid kit schema showed a price of about $12,449 vs page price $395 (theme code error, call 2025-12-04); schema missing on new kit pages (call 2026-04-09); still incomplete 2026-04-16; schema jobs completed 2026-04-23 on live theme (call 2026-04-30). Oversized cycle-life value in schema output being checked (call 2026-04-30).
- Variant data: corrected dataset approved for override (call 2026-06-25); active kits include Tiny Home, DIY bundle and 12V stacks. Creating a variant on an existing product changed its URL, so product URLs to be fixed and live products left unchanged (call 2026-09-10).
- Catalogue changes: new 475 W panel replaces older panels (call 2026-03-04); 5A active balancer SKUs to be removed; grade labels standardised to "Auto Grade" and "Solar Grade" (call 2026-10-22); add model/SKU to panel titles and URLs (call 2026-06-04). Jinko panel colour variants DV and DB; DB sent when DV out of stock (call 2026-06-04).
- Product descriptions were largely generic AI text; documents, videos and reviews sections empty (Sam, call 2025-09-11). Imported reviews show no activity in over a year (call 2026-09-10).
- Out-of-stock products can still be bought; out-of-stock message removed from cart page (call 2025-10-09).
