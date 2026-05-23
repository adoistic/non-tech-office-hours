# BitTorrent — Tech Performance Network Effects

**Concept:** [[tech-performance-network-effects]]
**Source:** raw/nfx-network-effects-manual.md

## What they built

BitTorrent is a peer-to-peer file transfer protocol released in 2001. Every device downloading a file simultaneously uploads pieces of that file to other downloaders (seeding). The more peers downloading a file, the faster every individual peer's download completes. The protocol requires no central server to store or distribute content.

## The mechanism

- Each new downloader is also a seeder: adding one user to a swarm adds bandwidth for all other users in proportion to that user's upload speed, making performance improve with scale rather than degrade.
- The protocol has no central bottleneck: removing the server removes both the scaling cost and the single point of failure, so performance scales out automatically as the network grows.
- Large, popular files attract more seeders over time, making the most-demanded content the fastest to download — a self-reinforcing quality loop.

## Why the analog often fails

Founders citing BitTorrent as evidence that "peer-to-peer architectures create network effects" need to be precise: not all P2P architectures create tech performance network effects. BitTorrent works because every consuming node is also a producing node by design. If the founder's P2P product has free-rider nodes that consume but do not contribute (common in consumer apps), the performance benefit does not materialize. The other miss: BitTorrent's tech performance network effect produced no durable business model for its creator. Strong tech performance network effects can make a protocol dominant without generating revenue for the protocol owner — a critical distinction for any founder building a business, not an open standard.

## Related examples

- [[examples/att-physical-network]]
- [[examples/google-data]]
