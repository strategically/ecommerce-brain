# Balloonery: feed state

_Facts from calls only. Dated; later calls supersede earlier. Counts that conflict are in open-questions._

## Merchant Center
- US feed audit on 2026-01-15: 16 products needed attention, one invalid price and 15 missing images (call 2026-01-15).
- Feed URL automation appends country=US; some feeds strip the parameter (call 2026-01-15).
- Detailed titles and attributes stay in the feed; website titles shortened separately; Merchant Center titles unchanged for now (calls 2026-01-29, 2026-02-12).
- Googlebot receives 404s on US product URLs, which blocks indexing and lowers PMax and Shopping quality; Canadian pages fetch correctly (call 2026-03-26). Likely cause is the geolocation or markets redirect blocking crawlers, not confirmed (call 2026-03-26).

## Metadata and schema
- Product metadata exists in the back end and needs checking (call 2026-08-12). Internal capitalised metadata fields must stay hidden; Canadian products need equivalent metadata, with schema and product-page implementation verified (call 2026-11-19).
- Occasion and other attributes mapped to schema markup (call 2026-01-29). Table of contents from attribute data on the product page, then schema, planned within two weeks of 2026-05-07 (call 2026-05-07).
- Shopify Markets filters products by country, so Canadian and Toronto-only products can appear on shared pages for US visitors (call 2026-11-05).
- Canadian product titles to be finished and re-indexed, mapping US titles across where they fit (call 2026-08-12).
