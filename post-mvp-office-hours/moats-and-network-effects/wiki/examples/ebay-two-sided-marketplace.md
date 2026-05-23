# eBay — Two-Sided Marketplace

**Concept:** [[two-sided-marketplace]]
**Source:** raw/nfx-network-effects-manual.md

## What they built

eBay is an online auction and fixed-price marketplace launched in 1995 connecting individual buyers and sellers of goods. It became the dominant venue for person-to-person e-commerce in the US by reaching liquidity early, then locked in participants through a feedback reputation system that was non-portable.

## The mechanism

- Each new seller expands the catalog of available goods, making the marketplace more valuable to buyers; each new buyer increases the probability a seller's item sells, making listing more attractive.
- eBay's feedback and star rating system created a portable reputation that was actually non-portable: a seller's hard-won reputation existed only on eBay and could not be migrated to a competitor, creating deep supply-side lock-in.
- Liquidity threshold: once eBay had sufficient buyers and sellers in a category, competing platforms could not match the fill rate, making alternatives structurally worse even with equal features.

## Why the analog often fails

Founders citing eBay as a comparable usually focus on the two-sided flywheel and underweight the reputation lock-in. eBay's most durable moat is not that buyers and sellers are there; it is that sellers built years of reputation that is worthless anywhere else. A "two-sided marketplace for X" without a portable-but-actually-trapped reputation layer is a much weaker business. The other miss: eBay's network effect is category-specific. A dominant position in vintage electronics does not automatically confer advantage in shoes. Founders often assume marketplace dominance is horizontal when it is almost always vertical.

## Related examples

- [[examples/craigslist-two-sided-marketplace]]
- [[examples/airbnb-two-sided-marketplace]]
- [[examples/uber-two-sided-marketplace]]
