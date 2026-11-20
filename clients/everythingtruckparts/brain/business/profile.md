# Everything Truck Parts: business profile

_Facts only, each with source and date. Current state as of the latest call (2026-11-10); superseded items are recorded in `../advertising/change-log.md` and `../decisions.md`._

## What the business is
- Online truck-parts retailer on Shopify with a very large catalogue; filters, cold air intakes, tonneau covers, running boards, floor mats, hitches, suspension and exterior accessories have all been discussed as categories (calls 2025-04-29, 2026-05-12).
- Many products are drop-shipped; Turn 14, Fleet Guard and a third-party warehouse are named supply routes (calls 2026-01-19, 2026-02-17).
- Some products cannot ship to California because they are not CARB compliant, for example certain cold air intakes (call 2025-06-30).
- Offline RFQ and large offline orders exist alongside online orders; offline orders are not tracked in analytics (calls 2025-09-05, 2026-03-26).
- Trade and repeat filter customers are a reorder-based revenue stream that John is working to replicate (call 2026-02-17).
- Reviews are collected through Target Bay; more than 3,000 reviews were reported (call 2025-04-29). Trustpilot is not used (call 2025-09-05).

## Category position (latest view)
- Filters are the priority line: highest margin, repeat purchase, and the focus of structured-data and feed work (calls 2025-06-30, 2026-02-17).
- Filter brands in focus: Fleet Guard, Donaldson, Baldwin, Wix (call 2026-02-17). Donaldson shows the lowest returns and best repeat behaviour and is the focus category for growth (call 2026-08-04).
- Filters are largely interchangeable between brands; when one brand is out of stock customers are often shipped another (call 2026-02-17).
- Cold air intake purchases tend to be one-off first orders (call 2026-02-17).
- Husky Liners and WeatherTech were described as cheaper and higher margin than filters (call 2026-04-14). Mishimoto, SkyJacker, Husky Liners and WeatherTech were profitable at current volume (call 2026-05-12).
- Flagged high-return or low-availability brands removed from promotion: ARB, AFE, PRP, Baja Designs, Husky Liners, Yukon (call 2026-07-21).
- Highest-return brands named on 2026-07-10: ARB, ICON, Fleetgast [sic], PRP, Mishimoto (call 2026-07-10).
- HPS and HBS are high-margin winners (call 2026-08-04).

## People and roles
- John (ETP): site operations, fraud management, Shopify store changes (call 2025-07-07).
- Bill (ETP): finance lead for ETP; concerned about ad spend and ROI (call 2025-06-17). A meeting with Bill was planned for the week after 2026-09-10 (call 2026-09-10).
- Sam (Strategically): analytics review, conversion recommendations, Google Ads, Merchant Center, enrichment (calls 2025-07-07, 2026-02-17).
- Mustafa (Strategically): technical changes, data analysis and optimisation; monitored daily spend in June 2025 (call 2025-06-17).
- Sami (Strategically): JSON-LD file creation (call 2025-06-30).
- Third parties named: Lakshay (developer, Donaldson scraper, call 2025-09-05); Danzsoft (data file, call 2025-09-26); Pius and Alex (front-end developers, calls 2025-09-26, 2025-11-04); Radi (external analytics contact, call 2025-07-07); Convermax contacts including Todd and Alex (calls 2026-07-23, 2026-08-18).
- Agency fee: about $2,500 per month in January 2026 (call 2026-01-19); reduced to $1,500 per month for three months from 2026-02-17 (call 2026-02-17).

## Platform and tooling
- Shopify store; Booster theme caused editor access issues and slower performance (call 2026-01-19). A new theme was previewed 2026-03-03 and described as faster; it removed many apps (calls 2026-03-03, 2026-03-26). Horizon was recommended as a modern theme (call 2026-01-19). Shopify Plus not signed up for now (call 2025-10-28).
- Matrixify for bulk import/export (calls 2025-08-26, 2025-11-04, 2026-09-16). Supabase holds scraped product data (calls 2025-09-26, 2026-06-23).
- Fitment and search: Convermax handles on-site vehicle fitment and search-bar functionality (call 2026-08-18). Spelling varies across notes; see open-questions.
- Email: Rejoiner (flows, pop-ups) approved 2026-08-04 (call 2026-08-04). Klaviyo cost concerns were raised (call 2026-05-26).
- Quotes go from PandaDoc to Outlook with no automated follow-up (call 2026-07-10).
- Review platform: Target Bay (call 2025-09-05). Tiered discounts are run by a third-party app (call 2025-07-22). Shopify search results pages are built by a third-party search app (call 2025-10-28).
- Tracking: server-side tracking via Stape.io with Google Tag Manager decided 2026-03-17 (call 2026-03-17).
- Competitors named: Summit Racing, Amazon (call 2025-06-17), Geno's Garage (call 2025-07-07).

## Known structural problems
- Bot traffic inflates Shopify session counts; Shopify and Google throttle bots, sometimes removing legitimate sessions (calls 2026-02-03, 2026-08-04).
- Checkout completion shows the largest funnel drop; shipping cost and returns are the suspected causes (calls 2026-04-14, 2026-05-12, 2026-07-21).
- Returns and cancellations materially reduce net revenue; drivers named are discontinued SKUs, out-of-stock listings, large cancelled orders, shipping and CARB compliance (calls 2026-03-03, 2026-08-04).
- Fraudulent orders are a recurring issue (call 2025-07-07).
