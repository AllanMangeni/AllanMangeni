## Allan Mang'eni

Infrastructure consultant and technical writer based in Nairobi. I work at the intersection of payment infrastructure, programmable settlement, and African fintech.

My current research focus is the migration of legacy webhook-based payment systems to synchronous, on-chain settlement using the x402 protocol. That means practical things: idempotency under network failure, cross-border settlement integrity on low-connectivity rails, and the architectural changes required to remove state management entirely from a payment integration.

---

### Active Research & Writing

**Programmatic Payments Series** — Published on [HackerNoon](https://hackernoon.com/u/allanmangeni)

A three-part series built from real implementation work, not theory:

1. [From Webhooks to x402](https://hackernoon.com/from-webhooks-to-x402-the-architectural-migration-equipping-autonomous-software-agents-for-the-agentic-economy) — The architectural case for dropping webhook-based payment rails and the cost in code complexity that legacy integrations carry.
2. [Stress-Testing x402 on Emerging Market Infrastructure](https://hackernoon.com/the-architectural-migration-equipping-autonomous-software-agents) — What actually happens when you run synchronous on-chain settlement over M-Pesa-connected networks. Latency data from Toxiproxy simulations included.
3. [The Idempotency Problem in African Cross-Border Settlement](https://hackernoon.com/u/allanmangeni) — The failure mode that survives the migration: facilitator timeouts, the three-outcome ambiguity problem, and a recovery state machine that handles exactly-once delivery without bringing the database back.

---

### Selected Work

| Project | What it does |
|---|---|
| [x402-migration-architecture-example](https://github.com/AllanMangeni/x402-migration-architecture-example) | Three-stage migration from Lithic webhook rails to native x402 settlement on Base. Reduces state management code from 15 lines to zero. Benchmarked with Toxiproxy. |
| [x402-migration-sandbox](https://github.com/AllanMangeni/x402-migration-sandbox) | Comparative analysis: legacy callback flow vs. autonomous x402 settlement. Quantifies code complexity reduction. |
| [Alusa](https://github.com/AllanMangeni/Alusa) | Parametric insurance protocol using agentic reasoning and the Stellar blockchain. |
| [avoid-ai-writing](https://github.com/AllanMangeni/avoid-ai-writing) | Agent skill that audits and rewrites content to remove AI writing patterns. Works with Claude Code, OpenCode, and Hermes. |
| [Akalysis](https://github.com/AllanMangeni/Akalysis) | Deployment cost and resource monitoring dashboard for the Akash network. |

---

### Technical Background

- **Payment infrastructure**: Safaricom Daraja B2C payout flows, idempotency implementation, webhook reconciliation, EIP-3009 Transfer With Authorization
- **Blockchain**: Solidity, Base, Stellar, Stacks, Filecoin/FVM, Algorand
- **Protocols**: x402, EIP-3009, M-Pesa Daraja API, USDC on Base Sepolia
- **Tools**: Node.js, TypeScript, Toxiproxy, Docker, k6

---

### Writing

Top 6 Finance writer on HackerNoon (Hall of Fame). I write about payment systems, cross-border settlement mechanics, and the practical engineering decisions behind African fintech infrastructure.

→ [HackerNoon profile](https://hackernoon.com/u/allanmangeni) · [Twitter / X](https://twitter.com/amw254)
