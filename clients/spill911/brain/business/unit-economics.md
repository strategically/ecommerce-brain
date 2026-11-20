# Spill911: unit economics

_Margins, fees, break-even. Source and date on every line. Currency not stated on most calls. Period-based performance figures (weekly or fortnightly sessions, revenue, spend, conversion) are not recorded here; they belong in the database._

## Margin and profit
- Gross margin is unresolved: the calls give 20%, 25%, 25-35%, 68-78% and about 75% cost of goods. All figures and the calls that conflict are in open-questions.md. Do not treat any as firm.
- Pricing is generated from cost with a VLOOKUP, and margin rises as cost falls since drop-shipping (Bill, call 2025-04-21).
- Pricing is set by ticket size, so larger items carry lower margin (Bill, call 2025-06-27).
- Calculations on later calls were run at a 20% margin (calls 2026-02-04, 2026-07-22); at 20 to 25% margins Bing conversions supported only break-even (call 2026-11-11).
- Break-even ROAS: stated as around 500 on 2026-01-07, unit unclear; see open-questions.

## Freight and shipping
- Pallet freight can cost around $300-400; some freight quotes are much higher than the item price; Bill said the company makes money on freight about 90-95% of the time (call 2026-01-07).
- Google requires a single shipping rate; a Google spot check that finds a lower on-site freight can get the feed dropped (John, call 2026-01-07).
- Shipping often exceeds product price and is the suspected main conversion barrier (call 2026-03-17). Free-shipping competitors attract price-sensitive searches; shipping reduces margin so some SKUs are unprofitable to advertise (call 2026-04-29).
- Legacy FedEx LTL display showed $1,400 where the new app returned $300-400 on a spot check (call 2026-05-29). An intermittent timeout produced an incorrect $6,000 freight quote (call 2026-06-10). One example: $625 freight on a $250 product caused drop-off (call 2026-08-19). A $2,400 abandoned cart showed a $1,100 quote under the new rates (call 2026-07-10).
- Echo API timing fails the Shopify 10-second response window (call 2026-05-29). Vendor responses on class and weight can delay quotes (call 2026-05-27).
- Freight efficiency scoring inputs: freight class, weight, origin and destination, product price; class 175 or above is a high penalty (call 2026-03-17).
- A $50 lift-gate charge needs customer approval before completing a Vestal order (call 2026-11-11).
- Voided ChatGPT-attributed orders came from shipping costs exceeding product prices, not channel performance (call 2026-11-11).

## Advertising economics
- Sam's rule of thumb: paid ads need about 10x ROAS (call 2025-06-11); John needs to see 10x before a campaign is worthwhile (call 2025-05-14). First-pass ROAS goal for scaled spend 8x (call 2026-08-19).
- Bing CPC about 2 to 3 cents against 30 to 50 cents on Google (John, call 2025-09-17). Moving to exact and phrase match expected to raise CPC about 4-5x, with an estimated 100 clicks per conversion for high-ticket items (call 2026-04-15). CPC cap $0.25 on exact-match campaigns (call 2026-04-29).
- About 80% of Google Shopping clicks estimated to be waste in April 2026, mostly generic B2C queries (call 2026-04-15). Sam earlier estimated 60 to 80% of account spend wasted (call 2025-04-21).
- Google-reported ROAS understates return because many orders are not tracked to Google (call 2025-06-11); see open-questions for conflicting ROAS statements.
- Gap between Shopify and Google conversion numbers over about 15% should be investigated (Mustafa, call 2025-06-11).
- Without closed-loop data (leads, offline deals), Google cannot optimise to cash outcomes against target ROAS (call 2026-09-16).

## Tool costs
- Stape server-side tracking about $20 a month versus current Shopify tag app $99 a month (call 2026-04-01).
- Filter app about $100 a month, cancellable after redesign (call 2026-11-11).

## Order value reference points
- Spill kits mostly under $500; single absorbents generally $200 or less (call 2025-05-14).
- Typical order a couple of hundred dollars, big-ticket orders several thousand (call 2026-07-10).
- Competitive pricing benchmark shows many SKUs priced below competitors (call 2026-03-04).
