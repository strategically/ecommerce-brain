# Spill911: pages and CRO tests

_Facts from calls only. Page-level traffic numbers live in the database._

## Collections and navigation
- Spill kits collection URL reverted from "all spill kits" to "spill kits" to protect ranking (call 2025-04-21). Dash-1 and dash-2 collection URLs come from a collection generated twice; remove the suffix where the base is free (call 2025-04-21).
- Facility and safety signs sit under PPE and safety and are to become a top-level category (call 2025-04-21). Material Handling has 15 subcategories (Hand Trucks 12, Pallet Trucks 13) (call 2025-05-15).
- Breadcrumbs drop higher levels on deeper pages; fix via parent, child and sub-child columns in the collection export, capitalised words, tested on Material Handling first (call 2025-05-15). Booster-side fix done, but each product still needs a category assigned by hand (call 2025-07-09). Shopify breadcrumbs drop collection context for direct product links (call 2026-04-15).
- Super grid views are static snapshots, rebuilt after collection changes (call 2025-05-15).
- Collection URLs for pads, booms, wipes and spill kits still to be corrected (call 2026-05-13).
- Left-hand navigation: lead with brand and use-case categories, drop price as a filter; filters built through Power Tools; product-type tags to be set up (call 2026-07-10).
- Collection page to be fixed first and rolled across the shop, then back to the homepage; Booster theme updated incrementally, not replaced (call 2026-11-11). Collection traffic converted poorly on 2026-09-30.

## Landing and hub pages
- Wet and dry vac (X Air) collection page as primary landing page; chemical storage collection page (call 2026-04-15). Paid traffic to collection pages was the 2026-04-15 plan; exact-match clicks to product pages or prefiltered collections from 2026-04-29.
- Railroad track pan page: V1 on product page, V2 subdomain landing page, V3 in Shopify (call 2026-05-13); not in main navigation, mainly ad-driven; page needs image fixes and Ultra-Rel mat products (call 2026-05-29).
- Spill containment hub page; shipping-promise banner comparing carrier rates; fix broken image caching on hub and product pages (call 2026-05-29). Developer cost and ETA requested for the spill containment page (call 2026-06-24).
- Spill kits overview page with filters (spill type: oil, hazmat, universal; size; portable or wheeled) and a "Build Your Custom Kit" funnel (spill type, quantity, customisation) generating a lead and custom quote (call 2026-06-10).
- Brand page rework and Vestal collection page rebuild (calls 2026-07-10, 2026-11-11).

## Product pages and templates
- Specification tables (dimensions, gallons, material, industrial use) and structured data pushed to Merchant Center (call 2026-04-15).
- Vestil product template used only for products with the required data structure and pricing: replace "Made in Spain" with part number, capacity, material or warranty; remove "In stock", shipping-origin and LTL messaging; email-gated downloads for engineering drawings and certificates; "email to purchasing or a colleague" beside price requests; trust points GSA contract, authorised Vestil dealership, price matching, 24/7 support; button text "Request a GSA quote" or "Request a formal quote"; black information blocks to red or clearer (call 2026-10-30).
- Part-number product pages for high-search Vestil items (call 2026-09-16).
- Request-for-quote: products tagged "RFQ-quote" show RFQ instead of add-to-cart; current RFQ app covers a couple of hundred SKUs and has no analytics (calls 2026-03-04, 2026-04-01). Planned RFQ widget with email, address autocomplete and cart contents (call 2026-05-27). Vestal RFQ step removed 30 June 2026 (call 2026-07-10). Quick freight estimate page removed (call 2026-05-29).
- Documents: product certificate link 404, other two document links work (call 2026-10-30).

## Forms, popups and email
- Contact Us form is the primary lead source (call 2026-09-16). Submitted forms should identify the originating product and route leads to John (call 2026-10-30). Spam and bulk RFQs among form enquiries (call 2026-06-24).
- Pop-up appears only for new users on time on page (about 10-15 seconds, John's estimate) or exit (call 2026-07-10). Rejoiner: first cart email text-only and immediate, next a day later (call 2026-07-10); browse emails about 30 minutes after visits (call 2026-09-16).
- Login-gated pricing test (proposed 2025-04-21); gate only larger-ticket items recommended, not decided (call 2026-03-04).
- Quotes sent as PandaDoc documents from Shopify draft orders (call 2026-07-10).

## Theme and site rules
- Attributes theme is a duplicate of the live theme used for enrichment before go-live (call 2026-05-13). Theme editor was failing in Oct 2025 (call 2025-10-29).
- Filter app about $100 a month may be cancelled once redesign replaces it (call 2026-11-11).
