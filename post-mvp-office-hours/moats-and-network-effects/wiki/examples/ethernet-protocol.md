# Ethernet — Protocol Network Effects

**Concept:** [[protocol-network-effects]]
**Source:** raw/nfx-network-effects-manual.md

## What they built

Robert Metcalfe at 3Com persuaded DEC, Intel, and Xerox to adopt Ethernet (IEEE 802.3) as the standard protocol for local area networks in 1980, with fixed speeds, 48-bit addressing, and a global Ethertype field. The product was a standard, not a device. Once adopted, every manufacturer had incentive to build Ethernet-compatible hardware because buyers expected it.

## The mechanism

- Once enough vendors adopted IEEE 802.3, compatible hardware flooded the market, driving costs down and accelerating adoption in a self-reinforcing loop.
- Competing proprietary standards (Token Ring, ARCnet) lost value as Ethernet captured share, regardless of technical merit.
- Switching from Ethernet would require every device on a network to switch simultaneously, making unilateral defection irrational.

## Why the analog often fails

Founders saying "we're establishing the protocol for X" typically skip the hardest part: Ethernet's adoption required coordinated sign-on from major incumbents (DEC, Intel, Xerox) before the market standardized. Without that early anchor coalition, a "protocol play" is just a product with API documentation. The other key miss: the protocol creator rarely captures most of the value. Metcalfe's Law made Ethernet valuable; 3Com captured only a slice. If the founder expects the protocol to generate revenue directly rather than creating a platform others monetize on top of, the business model is broken even if the network effect works.

## Related examples

- [[examples/bitcoin-protocol]]
- [[examples/att-physical-network]]
