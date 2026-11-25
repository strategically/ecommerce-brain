# Everything Truck Parts: advertising state

_Current state as of the latest call (2026-11-10). Each line is dated; later calls supersede earlier ones and the change is recorded in `change-log.md`. No weekly performance numbers. "Decided" means agreed on a call, not confirmed as executed._

## Channels
- Google Ads (Shopping, Performance Max, Search) and Bing (call 2026-10-13).
- Bing: steady conversions; Husky Liner and Wix campaigns performing well there (call 2026-06-23). Budget concentrated on the Bing Husky Liner campaign (call 2026-06-23). Duplicating campaigns to Bing otherwise waits until Google versions prove out (call 2025-10-28).
- Google spend and CPC were reported down and Bing spend slightly up; period not stated (call 2026-10-13).

## Current structure (latest first)
- Launch approach: complete vehicles year by year, Silverado first, then start advertising within one week for completed model years (call 2026-11-10).
- Campaign restructuring to remove non-converting catalogue spend (call 2026-11-10).
- Campaign structure per 2026-09-29: all-products campaign at high target ROAS; brand filter campaigns (part-number intent); vehicle-specific search and shopping to follow (call 2026-09-29).
- Year Make Model campaign prioritised, run alongside the high-ROAS campaign and PMax support (call 2026-10-13).
- Filter campaigns consolidated into one filter campaign with ad groups per vehicle or part (call 2026-08-18). Rebuild around vehicle-specific landing pages and single-keyword ad groups, within one to two months of 2026-08-04 (call 2026-08-04).
- F-150 campaigns by year with product-level landing pages (action, call 2026-08-18); F-150 landing page first, then Silverado and RAM (call 2026-09-10). F-150 kits stay unpublished until the page and new theme are ready (call 2026-11-10).
- Top-of-funnel "All products" campaign unchanged because of high return (call 2026-05-12); small budget increases approved for high-ROAS campaigns (call 2026-05-12).
- Husky and WeatherTech SKAG that includes all approved feed products left running for now (call 2026-05-12).
- Search campaigns for Baldwin, Wix and Fleet Guard at $10/day each; Donaldson left untouched (call 2026-06-09). Fleet Guard title and meta formula used as proof of concept before treating Baldwin and Wix (call 2026-06-09).
- New-brand testing campaign duplicated by product type: suspension, exterior accessories (running boards, fender flares), floor mats, hitches (call 2026-05-12). Suspension trimmed to Superlift and Tough Country; BMR paused or deprioritised (call 2026-06-09).
- Husky (new-brand) campaign $55/day toward $100/day, gradually (call 2026-06-09).
- Lift-kit branded campaign paused, to be rebuilt with single-keyword product-specific landing pages per vehicle fitment (call 2026-06-23).
- PMax remarketing for filter-page and fitment audiences planned (call 2026-06-23).

## Paused or off
- Skyjacker and BKK Performance paused; about $270 reallocated to HPS Performance (call 2026-06-09).
- Superlift, JKS Manufacturing and EBAC brand campaigns reported paused on 2026-06-09 (call 2026-06-23); see open-questions for the Superlift inconsistency.
- Bed Rug paused (stock and rebrand under Husky Liners); Banks Power off as unprofitable (call 2026-04-28).
- Fox campaign paused (call 2026-02-17).
- Baldwin air filters, Fleet Guard "all" catch-all shopping campaign (500 set) and Fleet Guard fuel water separator ad group paused (call 2026-02-09).
- Generic part-number-only keywords paused at scale where volume remains sufficient; replaced by brand plus part number in both orders (call 2026-04-28).
- K&N: kept running 2026-02-17 and 2026-03-17; reviewed for pausing 2026-04-28; current status not stated (calls 2026-02-17, 2026-03-17, 2026-04-28).
- Best Sellers campaign: proposed for removal 2026-05-26; no confirmation (call 2026-05-26).

## Product eligibility rules for paid
- Remove non-filter products under $100 from paid campaigns via a product label (call 2026-05-12). Proposed 2026-05-26 to move the threshold to $200, filters exempt, pending John's approval (call 2026-05-26).
- Low-ticket products below a dollar threshold excluded during the lift-kit rebuild; threshold not stated (call 2026-06-23).
- "Zombie" products (high clicks, no transactions) excluded from Shopping campaigns (call 2026-03-17).
- Brands removed from promotion: ARB, AFE, PRP, Baja Designs, Husky Liners, Yukon (call 2026-07-21). BF Goodrich removed from feed, with Mickey Thompson and Toyo to be audited (call 2026-08-04).
- Negative keyword list removing zip-code and apartment queries, with daily clean-up (call 2026-04-28).

## Bidding
- Raising filter target ROAS should be gradual, not one jump (call 2026-02-17). An increased ROAS target caused a performance dip and algorithm disruption (call 2026-10-13).
- Previous budget increases were followed by about seven days of poorer performance, so small incremental steps are preferred (call 2025-09-05).
- Specific target ROAS values stated over time conflict; see `../business/open-questions.md`.

## Conversion tracking and data quality
- Account uses purchase-only conversions since 2025-06-27 (call 2025-06-27).
- Server-side tracking via Stape.io with Google Tag Manager decided 2026-03-17, with a 1-2 week testing window (call 2026-03-17). Google Tag Manager showed urgent container quality issues (call 2026-03-26).
- Conversion data written into customer notes is to be fed back as extra signal (call 2026-03-26).
- Attribution gap suspected between Google Ads and Shopify, with confirmed Google-origin orders missing from Ads data (call 2026-03-03). Google removed transactions after they had appeared (call 2026-04-14).
- Bot traffic inflates sessions; reporting uses a human-only view (call 2026-02-03). Shopify intermittently throttles bots, marks product pages unavailable and disrupts Google ads (call 2026-06-23).
- A Cloudflare deployment caused Merchant Center product ID mismatches; removing it stabilised the feed (call 2026-08-04).
- UTM parameters are unavailable in conversion details for at least one order (call 2026-11-10).
- Shocks and struts, and Rhino, to be excluded from marketing (call 2026-11-24).

## Shared decisions with Spill 911
- Budget reductions on 2025-06-17 were agreed for both accounts; ETP side is in the change-log. Spill 911 detail lives in its own client folder.
