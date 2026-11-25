# Everything Truck Parts: enrichment rules

_Rules and standards stated on calls for product data, structured data and fitment. Current rule first; superseded rules noted. Each line is dated._

## Scope and priority
- Filters first (highest margin, best existing data), then other categories as feasible (calls 2025-06-30, 2025-11-04). Fitment data is a separate, later workstream (call 2025-11-04).
- Priority fields to normalise: MPN, brand, product type, UPC and packaging dimensions (call 2025-11-04).
- Fitment is the main data gap for filters because many also fit generators and manufacturing equipment; fitment is enriched from competitor and manufacturer sources found online (call 2025-06-30). Competitor sources named for Fleet Guard data: allprodiesel.net and FleetPride (call 2026-06-09).
- Shopify metafield enrichment targets OpenAI and other LLMs; JSON-LD on the front end targets Google Gemini and crawlers (call 2025-06-30).
- Staged plan: Stage 1 attribute extraction and rewritten Merchant Center titles per SKU; Stage 2 product highlights and detailed descriptions (call 2026-03-03).

## Donaldson
- Display order: brand, manufacturer part number and UPC first, then style, with the spin-on and efficiency test standard below; blank efficiency fields hidden (call 2025-10-28).
- Known scraper errors: efficiency test standard field holds micron values; brand missing on some records; unclear notes or series text (call 2025-10-28).
- Donaldson publishes dimensions in inches, feet and millimetres inconsistently, so dimension fields are hard to standardise (call 2025-08-26).
- Import rules: new SKUs imported via Matrixify as new products; attribute data appended to existing SKUs; scraper rebuilt to capture packaging dimensions, weight, UPCs and image URLs; scraped image URLs converted to Shopify-hosted images (call 2025-11-04).
- Metadata import complete as of 2025-11-25, pending developer validation (call 2025-11-25). Metafields were updated but not visible on the live site until the test theme is published (call 2026-01-19).

## Manufacturer part number and brand
- MPN and brand already exist in Shopify as SKU and vendor; map attributes from those fields rather than creating duplicate metafields (call 2025-08-26).
- For brands that use a three-character prefix, remove the prefix from the MPN, starting with the Turn 14 brands (call 2025-11-04).
- Multiple MPNs on one page may dilute the canonical MPN value (call 2025-11-25).

## SKUs and variants
- Shopify forbids duplicate SKUs (for the same vendor); duplicated products need a unique suffix or prefix, for example "-kit" or a brand letter (calls 2025-10-28, 2026-09-16).
- Product duplicates for engine/vehicle campaigns are renamed per vehicle and original listings kept (call 2025-10-28).
- Latest model for vehicle pages: single product per vehicle, with engine variants chosen from a dropdown that updates description and price; variant-specific descriptions in meta fields; master body HTML stays top-level (call 2026-09-29). This replaces one product row per engine size (call 2026-09-16).
- Sibling-brand product wording is about 85% similar by design, for variant SEO (call 2026-09-29).
- Two image levels: generic vehicle image with brand logos, and a variant-specific engine image; Design Option A chosen (call 2026-09-29).
- Images hosted on a CDN, with URLs supplied in Matrixify image columns; HTML description template for Matrixify imports (call 2026-09-16).
- Baldwin image URLs may fail Shopify imports and may need an alternative upload method (call 2026-11-10).

## Kits and bundles
- A kit is considered only when air, fuel and cabin filters are all present (call 2026-09-29).
- Keep brand-specific bundles (strong brand loyalty); a mixed-brand ETP bundle was rejected because of split drop-shipping costs (call 2026-09-16).
- Kits are built as bundles of their component filters via a bundling app, so components are separated for ordering (call 2026-10-27). Kit components appear on orders, packing slips and invoices (call 2026-11-10). Inventory stays disabled for filter kits because supplier availability is handled manually (call 2026-11-10).
- Bundle Lab versus Shopify meta objects is undecided (call 2026-11-10).
- Subscription offered as a post-purchase upsell; first order not discounted; avoid a free-shipping promise, highlight "save on shipping" instead (call 2026-09-29).

## Structured data (schema / JSON-LD)
- Remove all existing schema and replace it with one consistent implementation; only a single product markup block per page (calls 2025-07-14, 2025-07-22).
- Scope: item list, collection page, organisation, website, breadcrumbs, product and review markup; pricing and review schema first (call 2025-07-14).
- Tiered-discount products show the original price in schema; discounts managed manually via metafields if app data is not accessible at page load (call 2025-07-22).
- Reviews: use Target Bay only for review schema; remove Trustpilot references (call 2025-09-05).
- Use "compatible with" and related fields rather than "additional property" (call 2025-09-05).
- Relationships: cross-reference equivalents use "is similar to"; accessories or spare parts use "is accessory or spare part for" (call 2026-01-19). Filters link to the equipment they fit using accessory/consumable markup (call 2025-11-25).
- Current schema fields adequate for existing data: SKU, brand, price, condition, UPC and image (call 2026-01-19).
- Schema is implemented at template level, so theme changes require updates (call 2025-07-14). Front-end schema applied to Donaldson product pages first, after the data import (call 2025-11-04).
- Landing pages use stable year labels such as "2024-present" or "2024-26" to avoid frequent redirects (call 2026-01-19).

## Merchant Center titles and labels
- Merchant Center exposes 50-60 attributes; the first 60 characters of a title are the most critical (call 2025-11-25).
- Merchant Center titles do not overwrite Shopify product titles (call 2025-11-25). Titles and meta descriptions for Fleet Guard to be applied on product pages and in the feed, not feed-only (call 2026-06-09).
- Bestsellers tagged with custom_label_1 = bestseller, from Shopify order history so single large orders do not skew the list (calls 2026-03-17, 2026-03-26).
- A price label is needed because the feed and UI cannot filter by price directly (call 2026-05-26).
- Low-quality SKUs stripped from the feed; missing descriptions and inconsistent feed data have blocked some products (call 2026-07-21).

## Fitment
- Fitment built from AI scraping of forums and retail year/make/model listings, with an engine table per vehicle as anchor and four brands cross-referenced; AI assigns confidence levels and lower-confidence entries need manual verification (call 2026-09-16).
- Landing pages filter by year, make, model, engine and chassis date ranges; product tags added for Donaldson, Baldwin, WIX and Fleet Guard fitment (call 2026-09-10).
- Convermax needs a flat CSV upload to map fitment for Baldwin, Donaldson, Wix and Fleet Guard (call 2026-08-18). Held fitment items are narrowed or removed where manufacturer data contradicts the vehicle-year plan (call 2026-11-10).
- Selected vehicle stored in order note attributes today; moving to metafields under consideration (call 2026-10-13). Year, make, model and engine passed to the customer profile as separate backend fields (call 2026-10-14).
- Equipment-centred fitment matrix mapping four core filter types, starting with top-volume equipment (call 2025-11-25).
- Kit fulfilment lookup: each kit SKU maps to its component filters, grouped by brand; Fleetguard details go to a different fulfilment recipient than Baldwin, WIX and Donaldson (call 2026-11-24).
