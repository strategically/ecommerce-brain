# Abstract Ocean: enrichment rules

_Attribute schema, titles, import method and standing rules, as agreed on calls (2025-06 to 2026-11). Later rules supersede earlier ones; supersessions noted. Work is described as "Get Attributes" in call titles from 2025-10-13._

## Approach and method
- Plan: full clean-up and restructure of product metadata, standardised fields and category-specific templates, piloted on one category (call 2025-07-04). Structured data (attributes, schema, metafields) matters for SEO and future AI-driven commerce (call 2025-06-26).
- Attributes stored as Shopify metafields and tags, extracted by an AI workflow, imported with Matrixify (calls 2025-11-12, 2026-01-22). Workflow: add category metafields, create front-end schema markup, then upload AI-extracted data via Matrixify (call 2025-11-12).
- Matrixify imports are powerful but error-prone on large exports; export to CSV for manual review and fixes before any reimport (call 2025-11-19). Matrixify subscription reinstated 2025-11 (call 2025-11-12).
- One master EV category with merged metafields into a compressed EV schema and a PDP specification table (call 2025-10-22). Existing metafields were not mapped to a standard schema (call 2025-10-22).
- Attribute prefixes (for example size height, size width; fitment vehicle model) so related fields group together on the front end (call 2026-03-02). Metafields display alphabetically, limiting presentation control; related fields to be grouped into one product metafield (calls 2026-02-02, 2026-03-02).
- Metafield data reformatted to structured dropdowns and meta objects rebuilt, reconnected to the front end (calls 2026-02-23, 2026-03-02).
- Data enrichment completed for all products and front-end schema installed by 2026-02-09 (call 2026-02-09); a snapshot process does not reflect later inventory changes (call 2026-02-09). Filter extracts to active products only (call 2026-02-09).
- Version-two product data pass for more attribute granularity, with Pete approving (call 2026-05-11). Run full enrichment across remaining products, including previously out-of-stock items (call 2026-09-03).
- AI workflows built 2026-04: Product Description Writer, a Merchant Center optimisation triage tool and an enrichment dashboard; AI-generated SEO titles and metadata need Pete's approval before publishing (calls 2026-04-13, 2026-04-23).
- Fitment generated dynamically from product tags instead of manual PDP notes; 10 sample fitment conversions approved before bulk run (call 2025-11-12). Fitment details removed from benefits and descriptions (call 2026-02-06). Fitment needs a Universal or multi-select option for original versus refresh (call 2026-02-02).
- Front-end presentation is gated, giving about two to three days to correct issues after publishing (call 2026-02-06).

## Attribute schema (latest rules)
- Model generation labels: "Original" and "Refresh" across Model 3 and Model Y, "plaid" removed from labels (call 2025-11-19). Ranges noted on the call: Model S Original 2012 to 2020, Refresh 2021 to mid 2025; Model Y Original 2020 to June 2025, Juniper (Refresh) 2026 to present (call 2025-11-19). "Juniper" and "New Model Y Refresh" added to collection metadata and titles where appropriate (call 2026-08-17).
- Install difficulty standardised to four values: simple, easy, moderate, difficult, mapped from backend tags install1 to install4 (call 2025-11-19). Stored as a numeric tag 1 to 10 decoded to labels (call 2026-01-22). Install types 1 and 2 bucketed as under 15 minutes (5 to 15), type 6 and test-brace exceptions marked longer (call 2026-02-06).
- Install time buckets: under 5 minutes; 5 to 15; 15 to 30; 30 to 60; over 1 hour (call 2025-11-19).
- Vehicle area (also called application area) is one column with agreed core values and a generic default; values include front and rear bumper, mirror, window, door, dashboard, centre console, rear seats, trunk, frunk, footwell, interior and exterior (call 2025-11-19).
- Custom height, custom width and general dimensions removed as site-level attributes; dimensions stay on individual listings where needed (call 2025-11-19).
- "Customer acquired tools" attribute deleted; tool requirements go on product pages (call 2025-11-19). Supersedes the 2025-11-12 tools dropdown (screwdriver, trim removal tool, 10mm wrench, squeegee).
- Country of manufacture must be present for harmonised-code processes; canonical list China, Taiwan, Bulgaria, Indonesia, USA (call 2025-11-19). "USA made" appears only when the manufacturing location is USA, derived from the vendor (call 2025-12-05). Country of origin shown as USA, China omitted intentionally (call 2026-01-22).
- Automatic certification rule: all lighting products get CE and RoHS tags; other categories none except documented exceptions (call 2025-11-19).
- Warranty rules: screen protectors and lights lifetime-of-ownership cover; other products one year (call 2026-01-22).
- Remove the erroneous "intended for adults" flag; standardise colour, age group and material values (call 2025-12-05). Colour and finish standardised to a single value (example matte black) (call 2026-02-02). Colour detection only from product images, warranty normalised, ROHS noise removed, specifications as comma-separated lists (call 2025-11-17).
- Emblems classified as a subset of product type (badges and emblems); emblems are ABS, not stainless steel, per a metadata correction (calls 2026-02-06, 2026-02-02).
- Other attributes noted: tools required, installation difficulty, vehicle area, compatibility, finish texture, OEM versus aftermarket, features, benefits, length and size, fitment years, vehicle nicknames and model years (calls 2025-10-22, 2025-10-24).
- Attributes display inline, comma-separated, inside the product page accordion (call 2026-01-22).
- Category tags are mostly accurate with some protection crossover (call 2025-12-15). Smart-collection rules prioritise tags over product_type (call 2026-09-07).

## Titles
- Titles front-load make and model (for example Tesla Model Y) (call 2025-12-05); Merchant Center titles begin with the vehicle model (call 2026-02-02). Model and year front-loaded, inconsistent superlatives removed (call 2026-02-23).
- A 50/50 A/B test of control titles against optimised variants was planned (call 2025-12-05). Pete reviews proposed title changes before any Shopify product updates are pushed (call 2026-01-26).
- Titles and product data tracked 20 to 30 days then the bottom 50 to 60% re-cut (call 2026-02-23). Bottom 30 to 40% of Merchant Center products stripped and reprocessed (call 2026-03-30).
- Fitment or synonyms and search-term variants go into descriptions and custom meta fields (call 2026-09-03).
- "Accessories" added to micro-collection and standard collection titles (call 2026-05-18).

## FAQ and schema
- FAQ and People Also Ask extraction pipeline; FAQ broken out into separate metafields with FAQ schema (call 2026-04-06). FAQ meta object live on product pages, items 1 to 6 displayed (call 2026-06-08). Four prioritised FAQ questions per product, starting with PPF and screen protectors (call 2026-05-25).
- Consolidate multiple JSON-LD blocks per product into one and remove the hidden backend manufacturer field from JSON-LD (call 2026-09-03). Some products lack JSON-LD when out of stock because earlier enrichment runs skipped them (call 2026-09-03).

## Standing rules and guardrails
- Archive products with zero sales in 90 days (decided 2025-05-12); retire end-of-life SKUs before each snapshot (call 2025-12-05). Exclude EOL-tagged products from ads (call 2025-07-04).
- Initial Merchant Center upload in a batch of 100 low-performing products (50 optional); remaining products only after a control is in place and uplift is verified (call 2025-12-08).
- Make Merchant Center feed edits in small blocks and share the optimisation plan before pushing (call 2026-02-16).
- Do not push AI workflow changes automatically into production until confidence is higher (call 2026-04-23).
- Do not enable Merchant Center automated discounts (call 2026-04-27).
