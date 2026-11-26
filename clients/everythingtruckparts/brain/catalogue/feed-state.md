# Everything Truck Parts: feed state

_Merchant Center and catalogue state, latest first. Counts are as stated on the call and may not reconcile; conflicts are in `../business/open-questions.md`. Each line is dated._

## Merchant Center scope
- Drop-ship brands that reliably show in stock (WeatherTech, some K&N) are kept; filter the feed by brand availability, not only the in-stock flag (call 2026-01-20).
- Brands removed or flagged: Rhino, Thule/Tuli, Spider (immediate candidates, call 2026-01-20); ARB, AFE, PRP, Baja Designs, Husky Liners, Yukon (call 2026-07-21); BF Goodrich removed, Mickey Thompson and Toyo to be audited (call 2026-08-04).
- Proposed 2026-03-03: keep only Baldwin, Donaldson, Wicks [sic], Fleet Guard and K&N (call 2026-03-03). Not confirmed as done.
- Cancellations are well down after Merchant Center changes (call 2026-02-17). Turn 14 inventory has improved and cancellations decreased (call 2026-05-26).
- Sub-$100 non-filter SKUs stripped via label (call 2026-05-12); $200 threshold proposed (call 2026-05-26).
- A Cloudflare deployment caused product ID mismatches; removal stabilised the feed (call 2026-08-04).
- Missing descriptions and inconsistent feed data caused some products to be blocked or not pushed (call 2026-07-21).
- Banks products were out of stock, expected back around early March (calls 2026-02-09, 2026-02-17); John to tell Sam when they return (call 2026-02-09).

## Catalogue size and clean-up
- Plan to remove close to 60,000 products from three rarely sold brands (EBC Brakes, Wilwood among them) (call 2025-05-23); John referred to removing 90,000 products (call 2025-07-07).
- About 22,000 404s and deleted-product pages cause index bloat; redirect strategy undecided (call 2025-11-04).
- About 25,000 ad groups were created targeting part numbers (call 2026-04-28).
- Site search shows many part-number queries returning no results (call 2026-04-28); a Donaldson part number was searched 28 times with no results (call 2025-09-26).

## Brand data status
- Donaldson: price list has 7,099 SKUs, 5,602 in the current Shopify collection (call 2025-11-04). Metadata import complete pending developer validation (call 2025-11-25).
- Fleet Guard: 2,473 products still carry original body HTML (call 2025-11-25).
- Baldwin: about 5,600 products remained to process (call 2025-11-25); about 7,056 SKUs listed on the site and scrape to Supabase planned (call 2026-06-23); some descriptions not fully updated, many still show the original three bullets (call 2026-07-10); 571 Baldwin filters added as drafts, image scraping at one product every 20 seconds (call 2026-11-10).
- Processing rate about 300 products per day, campaign limit 100 per product type (call 2025-11-25). Earlier: 100 items per day per category with a 365-second cooldown (call 2025-11-04).
- 720 new products need descriptions, images, and length/width/height for freight (call 2026-07-10).
- Export of meta objects and body HTML for Wix, Baldwin, Donaldson and Fleet Guard to fix descriptions (call 2026-07-21).

## Vehicle kits (latest)
- 62 products and 353 variants imported on 2026-10-26 with zero errors, including 84 kit variants across Silverado, Sierra 1500 and Ram 1500; 115 variants held back (call 2026-10-27).
- 46 kits targeted; several blocked by missing SKUs, which also blocks CDN image generation (call 2026-09-29).
- About 2,300 placeholder weights (including 2,019 WIX items) overstate shipping; one Matrixify update is to correct them, and weight files must update both Shopify and the calculated-shipping app (call 2026-11-10).
- Silverado launch still missing kits, cabin filters, verification, QA and advertising; Ram 2013 to 2018 kits need naming, cabin-filter confirmation and engine images; Ram 1500 cabin-filter fitment unresolved (call 2026-11-10).

## Added by call extractor (2026-11-26)
- Filter kits launch without component SKUs or filter details shown; fulfilment gets a kit-SKU-to-component-filter mapping by brand (call 2026-11-24).
