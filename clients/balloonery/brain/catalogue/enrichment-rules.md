# Balloonery: enrichment rules

_How products are titled, enriched and organised, as agreed on calls. Latest rule kept; supersessions noted._

## Method
- Three sources merged to one record per product: Merchant Center export, Shopify product data and tags, partner-app component breakdown; a combiner joins them into one column for AI ingestion (call 2026-01-15). Join key: product title first (call 2026-01-15), then handle or ID (call 2026-04-23).
- Priority one from 2026-05-07: structured attribute data as metafields, populated, shown on the product page and written into schema (call 2026-05-07). Product descriptions left mostly unchanged; structured attribute data added (call 2026-04-23).
- Workflow: group products into buckets, infer attributes per bucket, populate metafields, add attribute tables to product pages, mark up schema (call 2026-04-23). 27 buckets, each with a title structure or a single-product title (call 2026-05-07).
- Shopify is the source of truth for attributes going forward (call 2026-05-07). Matrixify used to import metaobjects and export collections (call 2026-03-12).
- Attribute columns planned: manufacturer, size, colour, material, bundle (call 2026-04-23). Values include occasion, target group, gender (mixed, female, male, neutral), hospital-friendly yes or no, helium included (call 2026-05-07).
- Product metafield custom.country_location with allowed values US and Canada (call 2026-03-12).
- Customisable numbers and colours in titles are not fixed values (call 2026-01-15). Gender and custom-age tags drive collection filters (call 2026-01-15).
- Float durations by balloon: 11-inch latex two to three days, 16-inch latex one week, 36-inch latex two weeks, foil four days; a bouquet's float time is set by its lowest component (call 2026-05-07).
- Attribute data complete and installed, with US products optimised, by 2026-05-21 (call 2026-05-21; count in open-questions). Plan to replicate the process across Canadian products (calls 2026-05-21, 2026-08-12).

## Title rules (latest)
- Template: size, colour, design, print, helium-filled latex balloon; size always included (call 2026-05-21). Every title includes "helium filled" (call 2026-01-29). "Balloon" added to US titles on search-term research; Canada to follow (call 2026-08-12).
- Size at the end of individual, letter and number titles; weight left out of titles; latex and foil not called "accent" (call 2026-01-29). Ribbon and weight sit at the end so truncation drops them first (call 2026-01-29).
- Latex-only bouquets list all colours, maximum four (call 2026-01-29). Custom-colour products state that colours are custom; custom-quantity bulk products are titled "bulk" without quantity (call 2026-05-07). Reusable designation applies to foil only (call 2026-05-07).
- Titles must exclude inaccurate attributes, for example no ribbon on the Airwalker (call 2026-02-12). Occasion and other attributes also go into schema (call 2026-01-29).
- Piece-count rule is global across product types; duplicate occasion phrases fixed (call 2026-05-21).
- Detailed titles stay in the Merchant Center feed while shorter titles are used on collection pages (call 2026-01-29); Merchant Center titles stay unchanged for now and website titles are generated separately (call 2026-02-12).
- Process: per-product-type prompts tested on representative products (15 proposed) (call 2026-02-12); title work restarted from the clean attribute sheet, earlier review sheet discarded (call 2026-05-07); title tool infers rules from a sample, with approve, decline or edit per title and approve-all for simple categories (calls 2026-05-07, 2026-05-21). Tool to be handed to Shawn after fixes (call 2026-05-21).
- US titles rewritten around SEO and search-term research; re-indexing carries no SEO risk (call 2026-08-12).

## Descriptions and collections
- Descriptions written without bullet points in copy; bullets held on the back end (call 2026-05-21). Brand voice design document built during collection copy rewrite (call 2026-05-21).
- Collections re-imported as smart collections with tag-based rules; Sam creates a global tag, Shawn maps product tags to rules (call 2026-03-26). Collections link to at least two or three other collections (call 2026-05-21; earlier one or two, call 2026-05-07).
- Collection pages get occasion-specific filters and indexable collections (call 2026-11-19).
