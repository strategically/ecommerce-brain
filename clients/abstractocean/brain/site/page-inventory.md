# Abstract Ocean: pages and CRO tests

_Collections, product pages, themes, apps and conversion tests, as stated on calls. Latest state first within each block. Pete implements theme and page changes; Sam supplies recommendations, data and ad work._

## Theme and platform (latest first)
- Draft theme with UI changes (lowercase typography sitewide, tighter mobile spacing, sticky image panel with arrows) not yet live as of 2026-07-31; sticky add-to-cart allowed adding without choosing a variant, to be fixed so add-to-cart needs an explicit variant (call 2026-07-31). GitHub repository for a theme change audit trail planned (call 2026-07-31).
- Shopify Horizon preferred over paid themes for future-proofing; headless test store considered for a separate armour or Cybertruck range (call 2026-05-11).
- Mobile-first fresh theme alongside the current site decided 2025-12-19, with a garage-style model-specific experience (call 2025-12-19). Slow theme migration completed 2025-10-28; front-end theme out of date and custom tab code conflicted with it (call 2025-11-07).
- Cloudflare: www record to DNS-only with CNAME to shops.myshopify.com (call 2026-07-13). Bot protection later removed, inflating sessions (call 2026-07-27).
- Page size and scripts slowing the site; images moving to medium-resolution JPEGs; missing alt text, duplicate JSON-LD on homepage and missing Open Graph tags flagged by an automated audit (call 2026-03-23). Image viewport audit and a responsive image app to be chosen (call 2026-08-03).
- Page load worsened by about two seconds after the 3PL updated its app (2025-05-14) (call 2025-05-14).

## Navigation, collections and landing pages (latest first)
- Collections: about 143 imported and prepared via smart rules using tags (call 2026-09-07); 42 of 71 collections underpopulated, no collections with fewer than about four products, vehicle tag plus category tag required (call 2026-09-21); collections still not implemented on the store as of 2026-09-28, with Pete to add the missing ones (call 2026-09-28). Earlier recommendation of about 75 collections for model-by-application coverage (call 2026-09-03).
- Duplicate collections reduced from about 72 to about 61; indexed /all/* collection pages removed; duplicate screen-protector collections merged with redirects (call 2026-08-03).
- Top-level collection pages carry inline text links to sub-collections (descriptions about 130 to 150 characters) and each sub-collection links back to its parent (call 2026-09-03). Internal link map confirmed correct 2026-09-21 (call 2026-09-21).
- Top-level Tesla landing page with a vehicle chooser proposed, Rivian equivalent later (call 2026-10-05). Overlapping Cybertruck collection pages: keep interior accessories, redirect the duplicate armour page, remove two bundle pages (proposal; call 2026-10-05).
- Cybertruck collection redesigned 2 to 8 October; conversion, pages per session fell and bounce rose afterwards (call 2026-11-02). Cybertruck collection to get a clearer "Build your protection" call-to-action and consistent savings language (call 2026-11-02).
- Breadcrumb navigation on product pages is a high-priority SEO ticket (call 2026-08-03).
- Left-hand filters on desktop being considered; mobile needs separate thought (calls 2026-08-03, 2026-10-05).
- Lights collection re-architected with model-specific navigation and filters; model-specific landing pages for lights and screen protectors (call 2026-02-09). Screen protector landing page to be reworked with clear H1, four model and size blocks, benefits, reviews and FAQs (v0.2) (call 2026-05-25).
- PPF landing page: collection existed but was not surfaced; dedicated page built (calls 2026-03-23, 2026-03-30). DIY PPF asset and listings added (call 2026-03-02).
- Header and home: header imagery judged busy (call 2025-04-25); homepage redesign deployed by Pete 2026-01 (homepage only page changed) with an 80px trust banner and a directive "Select your vehicle model" CTA (call 2026-01-12). Remove or keep the top header banner and year-make-model finder is undecided (call 2026-08-10).
- Returns & Exchanges moved out of the top-level header back to a less prominent place (call 2026-08-17).
- Collection ranking: a sorting app re-sorts collections every two hours by revenue potential and was surfacing low-margin samples (calls 2026-01-12, 2026-08-03).

## Product pages and bundles
- Model Y "build your bundle" product live and generating revenue by 2026-08-10 (call 2026-08-10); Build Your Bundle proposed as the primary CTA in collections (call 2026-08-10). Bundle add-to-cart is high but conversion low; discount badge not clearly shown in checkout; Cybertruck bundle had no conversions in the week of 2026-08-17 (call 2026-08-17).
- New builder funnel for Cybertruck: a subtle builder link or button on component product pages placed higher, PPF option selection kept required, homepage banner considered (call 2026-10-12). Legacy bundler still used by some customers (call 2026-10-12).
- Three simplified bundle tiers (basic, mid, ultimate) proposed as a test; Explorer Ultimate product page redesigned with a sizzle reel and visible add-ons, to publish after the sale (call 2026-09-07).
- Frequently-bought-together: logic missing on most product pages (call 2026-10-05); feature unfinished as of 2026-11-09, suggested products to remain unselected by default, capped at four, using vehicle fitment (call 2026-11-09).
- Product page upsell ("Pete's Promise" seller protection) test on Armor products first (decided 2025-06-18) (call 2025-06-18). A post-purchase upsell app broke tracking and was removed the Monday before the 2025-10-01 call (call 2025-10-01).
- Free gift with purchase explored for Black Friday 2025 (call 2025-09-04).
- Attribute display: a product attribute tab was preferred (call 2025-10-17), then a temporary accordion or widget under the install guide button because the tab conflicts with the theme (call 2025-11-07), then inline comma-separated attributes in the product page accordion (call 2026-01-22).
- Install difficulty indicators changed to show green (call 2025-07-11). Product page videos: installation video planned (call 2025-04-25); 2 to 5 thirty-second clips to be published (calls 2026-07-20, 2026-08-10); installation guides linked on product pages via QR codes (call 2026-08-17).
- Reviews: Junip reviews live with customer photos and videos (call 2026-08-03). Review summary in draft theme replaces a $30 review app (call 2026-07-31).
- Model Y screen protector pages: customers confirm screen size via a metafield popup (call 2026-04-06). A notify button shows when out of stock (call 2026-02-09).
- Superhydrophobic camera cover is the SEO test case: optimised description, title and on-page FAQ gave early impression and click gains; monitor four weeks before wider rollout (call 2026-04-06).
- Emblem ordering to be hidden behind a login or members-only area; the current flow is manual (call 2026-09-14).

## Vehicle selector and personalisation
- Persistent full-screen vehicle selector with cookies replacing the four-click model picker (decided in the mobile-first retheme plan 2025-12-19) (call 2025-12-19). Vehicle-first pop-up flow in 2025-09 asked vehicle type before email (call 2025-09-15).
- Pathfinder garage writes vehicle tags into Shopify customer records, but login is required; year-make-model tagging covers only about 0.7% of customers; paid YMM app could be replaced with custom logic (calls 2026-07-27, 2026-07-31).
- "We think you drive X, is that correct?" popup with save to account or cookie proposed, with a possible sign-up incentive (call 2026-08-10).
- Delivery / new-owner checklist: gated download capturing vehicle model, Glide app built with Perplexity, PWA version to finalise; 20 downloads recorded (12 Cybertruck, 6 Model Y, 2 Model 3) (calls 2026-02-16, 2026-02-23, 2026-09-28, 2026-11-02). New Owner app on a third-party platform to be simplified and relaunched within 30 days (decided 2026-06-01) (call 2026-06-01).

## Email capture and forms
- Email pop-up 13 seconds after landing (previously 50% scroll, 30-day suppression); target capture 15 to 20% (call 2025-08-15). Sign-up incentive 15% off (call 2025-10-09).

## Help, support and content
- Help content migrated back on-site from Redo; returns stay on the Redo portal (call 2026-08-17). In-house help desk on Cloudflare covers email, SMS and live chat (call 2026-10-05). Plan to replace the Redo helpdesk with a Claude-assisted workflow (call 2026-09-14).
- Blog: Model Y Performance centre-screen install post (call 2026-01-22); buying guides failing FAQ rich result schema (call 2026-06-08); delivery-checklist blog post (call 2026-11-02); a robotaxi blog post produced a rapid traffic spike (call 2026-09-07). Content ideas: insurance cost by state, resale-value estimator, FSD update tracker, maintenance guides (call 2026-09-28).
- Competitor data and AI visibility: AI visibility audit scored the store 45/100 against 48/100 for a competitor (call 2026-05-25).

## Tests on record (outcomes where stated)
- Homepage redesign: bounce fell about 6 to 8% relative, but add-to-cart and conversion fell; sample of a couple of hundred sessions judged too small (call 2026-01-12).
- Roof trim image test and embedded installation guide split test (7-day), decided 2025-06-06; outcomes not recorded (call 2025-06-06).
- 50/50 title test, planned 2025-12-05; outcome not recorded (call 2025-12-05).
- Profile-backed targeting A/B on a duplicated asset (call 2025-10-24); outcome not recorded.
