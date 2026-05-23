# Airbnb — Two-Sided Marketplace

**Concept:** [[two-sided-marketplace]]
**Source:** raw/nfx-network-effects-manual.md

## What they built

Airbnb is a short-term rental marketplace launched in 2008 connecting hosts with spare rooms or properties to travelers seeking accommodation. Hosts list and set prices; guests search and book. Revenue comes from service fees charged to both sides. It operates globally with inventory in over 100,000 cities.

## The mechanism

- Inventory is asymmetric and geographically fixed: a host listing in Lisbon adds value for travelers going to Lisbon, not for travelers going to Tokyo, making the network effect destination-specific rather than global.
- Review and trust systems create supply-side lock-in analogous to eBay: a host's Superhost status and accumulated reviews are worthless on competing platforms, raising the cost of multi-tenanting.
- Demand-side density in popular destinations makes Airbnb the default search surface; once enough travelers start their search on Airbnb, hosts cannot afford not to list there.

## Why the analog often fails

Founders citing Airbnb as a comparable tend to underestimate how hard the trust problem was to solve. Airbnb spent years and significant capital building the review system, photography standards, host guarantee programs, and identity verification that made strangers trust strangers with their homes and stays. A "marketplace for X" that requires similar trust between strangers without a credible trust infrastructure is not comparable to Airbnb — it is at the starting line Airbnb was at in 2008. The other miss: Airbnb's inventory scales without capital (hosts supply their own assets), which is the structural advantage over hotels. If the founder's supply side requires Airbnb-style capital deployment, the unit economics break.

## Related examples

- [[examples/ebay-two-sided-marketplace]]
- [[examples/uber-two-sided-marketplace]]
- [[examples/craigslist-two-sided-marketplace]]
