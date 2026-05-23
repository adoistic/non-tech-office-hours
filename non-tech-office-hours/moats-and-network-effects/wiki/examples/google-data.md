# Google — Data Network Effects

**Concept:** [[data-network-effects]]
**Source:** raw/nfx-network-effects-manual.md

## What they built

Google's search product indexes the web and ranks results using PageRank plus a continuously updated click-through and engagement feedback loop. Every search query and subsequent click teaches Google which results are relevant for which queries, improving future rankings. More searches produce better results, which attract more searches.

## The mechanism

- Each user query generates behavioral data (clicks, dwell time, reformulations) that refines ranking models; this data is only available to the entity processing the queries, creating a data moat that grows with scale.
- PageRank used the link graph of the entire web as a distributed signal; as Google indexed more pages and processed more queries, the signal got richer and more accurate.
- The feedback loop is continuous and self-improving: errors in ranking are corrected by aggregate user behavior faster than a competitor starting from scratch could match.

## Why the analog often fails

Founders claiming data network effects often conflate having data with having a data network effect. Google's data moat requires that more usage produces more useful data in a closed loop. If the founder's product collects more data but that data does not demonstrably improve the product for users, there is no network effect — only a scale advantage. The second miss: data network effects are asymptotic in most domains. Past a certain volume of data, marginal queries improve accuracy minimally. Founders should identify the specific product dimension where more data measurably improves user experience, not assume data accumulation is inherently defensible.

## Related examples

- [[examples/google-language]]
- [[examples/bittorrent-tech-performance]]
