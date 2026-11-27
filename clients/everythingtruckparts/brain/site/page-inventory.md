# Everything Truck Parts: pages and CRO tests

_Site state, pages and conversion tests, latest first within each section. Each line is dated. No weekly performance numbers._

## Theme and platform
- New theme previewed: faster, richer fitment attributes, improved choose-vehicle flow and brand landing pages (call 2026-03-03). It removed many apps, improving performance and cutting app costs (call 2026-03-26). Launch was hoped for the end of February 2026, not firm (call 2026-02-17).
- Old Booster theme caused editor access issues and slow performance; test theme to be published once the schema audit is complete (call 2026-01-19). Two freelance developers shortlisted at fixed quotes of $750 to $1,000 for the migration; vendor selection open (call 2026-01-19).
- A theme update caused font and schema breakages after merges; the developer recommends moving custom code out of the theme (call 2026-05-12). The find page schema and update approach are pending (call 2026-05-12).
- F-150 kits stay unpublished until the page and new theme are ready (call 2026-11-10).

## Vehicle and kit pages (current build)
- Order of rollout: Silverado lead, then year by year (call 2026-11-10); earlier Ram 1500 was lead (call 2026-10-27); F-150 page first (call 2026-09-10); Tacoma 2016 to 2023 top-level page with category navigation and filters (call 2026-10-14).
- Layout: large vehicle image left, bundle and individual products right; modal asks year then engine before filters show (call 2026-10-13). Top-level vehicle pages link to subcategories and filter pages (call 2026-10-13).
- Tacoma page contents: replacement schedule copy, why-buy content, contact information, FAQs; Save To My Garage, change-vehicle and engine selector (call 2026-10-14). Ads link to chassis or static filter pages with a pop-up confirming the vehicle (call 2026-10-14).
- Kit pages: F-150 bundle page with four brand options (call 2026-09-16); engine variants via dropdown (call 2026-09-29); each product approved before going live (call 2026-10-27).
- Prototype vehicle-to-filter-to-product landing page works out filters and SKUs from make, model and year with a confidence score and optional engine field; options are a subdomain test or full Liquid conversion (call 2026-04-14).
- Fitment-driven search-parameter URLs route uncertain matches to a filtered search page (call 2026-08-18).
- Bundles of air, fuel and cabin filters to raise average order value (call 2026-09-10).

## Homepage (2026-02-03 design decisions)
- Prioritise vehicle selection with a centred call to action "Find parts for your vehicle"; move vehicle search bar into the header above the fold with copy "Choose your vehicle" and "Click your brand below"; brand tiles as obvious "Select" buttons; reduce hero height; "Shop by category" limited to four top categories; remove weekly "Deals" banner; brands in three rows (call 2026-02-03).
- Landing-page experience does not match search intent and needs redesign (call 2026-09-10). Homepage bounce rate was judged too high (call 2025-04-29).

## Product page
- Missing fields added but some data hardcoded; inner diameter pulled from the wrong field; unnecessary options, social icons and dead "view parts" links to be removed (call 2025-08-26).
- Donaldson display order is in `../catalogue/enrichment-rules.md`.

## Search and fitment
- X Cloud Search does not index meta objects by default; owner open to adding it; search component planned to accept part numbers and vehicle make/model with attribute filters on the left (call 2025-09-26).
- Brand drop-down filters were not showing at the top of search results; cause unknown (call 2025-10-28).
- Convermax: vehicle garage persists via cookie or app integration; persistence in incognito uncertain (call 2026-10-14). Vehicle data written to Shopify order "additional details" and customer meta fields, inconsistently (call 2026-07-23).

## Cart, checkout and CRO tests
- Name requirement before shipping rates removed as a trial; John to monitor for one week (call 2025-07-07). Result not recorded in the notes.
- Theme change moved cart behaviour to a mini-cart/sidebar (call 2025-07-07).
- Checkout completion shows the largest funnel drop; shipping and returns suspected (calls 2026-04-14, 2026-05-12).
- Test orders were rejected with "cannot ship to this location" and shipping errors; checkout shipping settings, free-shipping rules and freight estimates to be reviewed (call 2026-03-26).
- Rejoiner pop-up live with deliverability reported high; emails sent from a dedicated subdomain (call 2026-08-18). Flows approved 2026-08-04: cart and browse abandonment, welcome series, pop-ups (call 2026-08-04).
- Goal: capture email at vehicle save or through an exit-intent popup (call 2026-07-21). Whether Convermax can do this is open (call 2026-10-14).
- Reviews through Target Bay; request at order placement, reminder after 7 days (call 2025-04-29).

## Added from call 2026-11-24
- Filter-kit pages: engine selection as pills; kits organised by chassis with only applicable kits shown; component SKUs and filter details hidden; no volume-pricing display on kit pages, kept on other filter pages (call 2026-11-24).
- Fitment table to be filtered to engines applicable to the selected chassis (call 2026-11-24).
