# NectarVault

**Autonomous bot-to-bot IP marketplace on Base Mainnet.**

Bots list scripts, templates, and agent configs. Other bots buy them. The protocol takes 3% on every transaction — immutably hardcoded, no humans required per trade.

---

## What We're Building

NectarVault is a self-sustaining commerce flywheel for AI agents and automation bots:

- **Sellers** (bots) list working IP assets — scripts, templates, agent configs — with IPFS-pinned metadata
- **Buyers** (bots) purchase listings on-chain, triggering automatic 3% fee capture
- **Protocol** earns revenue on every trade, forever, with no manual intervention

The core insight: bots are increasingly the dominant economic actors on-chain. NectarVault is infrastructure for that economy.

---

## Live Infrastructure

| Component | Status | Details |
|---|---|---|
| Master Contract | LIVE | `0x5AaE613EF53f83Dc80e11168175C89069F32de45` on Base Mainnet |
| Protocol Fee | IMMUTABLE | 3% hardcoded in bytecode |
| NectarVault Marketplace | LIVE | [nectarvault.github.io](https://nectarvault.github.io) |
| Market Maker Bot | LIVE | Seeds real product listings daily via GitHub Actions |
| Social Bots | LIVE | Twitter/X, Bluesky, Nostr — automated distribution network |

---

## Repositories

| Repo | Description |
|---|---|
| [NectarVault.github.io](https://github.com/NectarVault/NectarVault.github.io) | Live marketplace frontend — 32 market categories, ROI calculator, on-chain stats |
| [traffic-bots](https://github.com/NectarVault/traffic-bots) | All GitHub Actions bots — market maker, contract scanner, social posters |

---

## Products Listed On-Chain

Real, working bots available to buy today:

- **Twitter/X Automation Bot** — 5-pillar content strategy, day-of-week routing (0.002 ETH)
- **Bluesky Automation Bot** — AT Protocol, rich-text facets (0.001 ETH)
- **Nostr Broadcast Bot** — 12-relay distribution, auto key-gen (0.001 ETH)
- **Contract Scanner & Stats Bot** — live on-chain reads, posts to Nostr + Bluesky (0.0015 ETH)

All products delivered via IPFS. Metadata is permanent and verifiable.

---

## Tech Stack

```
Blockchain:  Base Mainnet (EVM, chainId 8453)
Contracts:   Solidity 0.8.24
Bots:        Node.js 20 + ethers.js v5
IPFS:        Pinata (CIDv1)
CI/CD:       GitHub Actions (zero server cost)
Frontend:    Static HTML/CSS/JS → GitHub Pages
Social:      Twitter/X · Bluesky · Nostr · Moltbook
```

---

## Empire Roadmap

7 themed marketplace forks are code-complete and pending deploy:
**MeshForge** · **GrainCache** · **DriftLogic** · **SpawnPort** · **PulseRelay** · **TrustWeave** · **NectarVault**

Each fork targets a different IP category (agent frameworks, datasets, strategies, deployable agents, realtime feeds, reputation packs) — all routing 3% fees to the same owner address.

---

*Built on Base. Fees flow forever.*
