# Spill911: enrichment rules

_How products are enriched and titled, as agreed on calls. Latest rule kept; supersessions noted._

## Attribute structure
- Three tiers: company (core SKU, MPN, product metadata), business (Spill911 operations and brands), category (spill containment, absorbents, material handling) (call 2025-10-01).
- Keep the core attribute set small to avoid an unmanageable structure across the catalogue (call 2025-07-09); attributes that do not apply to every product are dropped from the universal table, for example load-bearing capacity (call 2026-01-07).
- Roll out the 80/20 way: most valuable attributes across the catalogue first, detail later (proposed, call 2025-07-23). Enrich in small product sets to keep accuracy high (call 2025-09-17). Blocks of about 5,000 products, extraction then import (call 2026-01-07).
- Start with spill containment (call 2025-10-01), then absorbents in the Attributes theme (call 2026-05-13); top 1,000 SKUs first for the enrichment tool (call 2026-04-29).

## Core nine (spill containment, first extraction)
Vendor (brand), manufacturer part number, benefits and features (short bullets), dimensions (length, width, height), shipping weight, containment capacity (gallons), material, colour, manufacturer's warranty (years) (call 2025-10-29).
- Category attributes later: load-bearing capacity, drum compatibility (one, two, IBC), stackability, chemical-resistance specifics, certifications, portability or reusability, drain, grating and forklift pockets, UV and rust resistance (call 2025-10-29).
- Earlier fuller lists: containment type, foldable, fork pockets, EPA/OSHA/FM certifications, origin, warranty (call 2025-10-01); material-handling: handling type, load capacity, lift height, platform length, wheel type, diameter and count, swivel and brakes, corrosion resistance, temperature rating (call 2025-10-01).
- EXAIR fields: product line, material, OSHA compliance, temperature rating, air consumption, operating pressure, inlet connection, product base (call 2026-05-13). Absorbents: category (oil-only, universal, hazardous), dimensions, units per case, absorption capacity, brand, delivery lead time (call 2026-05-13).
- Extraction tool can also add warranty, technical specs, hazmat and regulatory flags; it avoids guessing and uses only certain data; group approval workflow (call 2026-04-29).
- Extraction reliability: gallons, certifications, application good; country of origin and weight not reliable (call 2025-07-23). Country of origin is needed for government reporting and is available internally (John, call 2025-07-23).
- John to ask Peabody for missing attributes such as dimensions, lid opening and mounting; Peabody supplies no GTIN/UPC (call 2025-07-23).

## Method and data handling
- AI reads titles, images, vendor pages and part numbers (call 2025-10-01); Shopify metaobjects and meta fields hold attributes (call 2025-07-09).
- Shopify handle is the unique identifier for merges; bulk updates via Matrixify (call 2025-10-29). Take a full Shopify export first as a backup (call 2025-12-11).
- Clean before import: strip "NA", standardise units (inches), remove bad values, parse shipping dimensions out of the Additional attributes column into discrete fields, map manufacturer part number to the historic Shopify field (call 2025-11-12).
- Test on a preview or Attributes theme (a duplicate of the live theme) before going live (calls 2025-11-12, 2026-05-13).
- Front-end spec table: height, width and length first, warranty lower (call 2025-11-12); front end needs a simple attribute table (call 2026-04-29).
- Schema: add manufacturer part number first (call 2025-09-03); fix price with comma and missing "valid until" (call 2025-09-03); verify product schema before finalising templates (call 2026-10-30).
- Pricing sample export columns: buy price, lowest comparable price, recommended price, current web price, calculated gross margin (call 2026-01-21).
- Tag marking titles as updated attempted; test failed on a JSON and data-type mismatch; tag format to confirm (call 2026-01-21). Title work runs on a snapshot, so newer products are not picked up (call 2026-01-21).

## Titles
- Update titles in Shopify first, then export to a Merchant Center supplemental feed; SKU and part number unchanged for order matching (call 2025-12-11).
- Brand and key specs first; Vestal and Peabody top priority, Vestal worst (call 2026-01-21). Limits then: about 66 characters visible, 150 total (call 2026-01-21); later batches use 200-character titles with about 6 attributes (call 2026-03-04). See open-questions.
- Consider multipack and colour for filtering (call 2025-12-11). New products get the manufacturer name at the front of the title (call 2026-07-10).
- Track titles against a control; flagged SKUs go to manual review and titles can be rebuilt from original attributes (call 2025-12-11).

## Vestil data import
- Metafields and metaobjects must exist first; required fields include package and assembled dimensions and feature/benefit text (call 2026-09-30). 28 metafields, four warranty PDFs, a 10-row test, then the full 5,977 products plus 1,030 video files (call 2026-10-14). Bill reviews and signs off the test (call 2026-10-14).
- Images by Dropbox URL in a CSV image column, multiple separated by semicolons; Shopify serves via its CDN (call 2026-09-30). Correlate image IDs to SKUs first (call 2026-09-30). Files: images, warranties, manuals, MSDS/SDS, engineering drawings (call 2026-09-30).
- Product-specific PDFs uploaded as content files via a Matrixify export; fix the certificate 404 (call 2026-10-30).
- Update existing website products first; newly added products stay draft until priced by Bill (call 2026-10-30).
- Complete product enrichment before pushing the feed (call 2026-10-14). Publish enrichment metafields to Shopify and overlay the enriched feed in Merchant Center, keeping the existing Simprosys feed (call 2026-04-29).
- Add brand names to titles of about 16,000-17,000 products lacking one, keeping a space between brand and product name, and apply product taxonomy (call 2026-11-25).
- Leave the Shopify agentic-catalog field configuration unchanged for now (call 2026-11-25).
- Standardise core fields (dimensions, weight, materials, safety information) first, then brand- and product-specific information, reflected in storefront and schema (call 2026-11-25).
