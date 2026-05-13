## About

Nairobi-based infrastructure consultant and technical writer. My work sits at the intersection of programmable payment settlement, open-source protocol infrastructure, and African fintech.

Current research focus: the failure modes that survive the migration from webhook-based payment rails to synchronous on-chain settlement using the x402 protocol — specifically idempotency under network failure, cross-border settlement integrity, and the recovery architecture required when a facilitator times out before the chain confirms.

Top 2 Finance writer on [HackerNoon](https://hackernoon.com/u/allanmangeni) · ~4M monthly readers · 2022 Smart Contract Contributor of the Year runner-up · Algorand Foundation grant recipient · Ecosystem builder across East and West Africa developer communities

---

## Tech Stack

### Blockchain & Protocols
![Solidity](https://img.shields.io/badge/Solidity-%23363636.svg?style=for-the-badge&logo=solidity&logoColor=white) ![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=Ethereum&logoColor=white) ![Bitcoin](https://img.shields.io/badge/Bitcoin-000000?style=for-the-badge&logo=bitcoin&logoColor=white) ![Stellar](https://img.shields.io/badge/Stellar-090E17?style=for-the-badge&logo=stellar&logoColor=white) ![Web3.js](https://img.shields.io/badge/web3.js-F16822?style=for-the-badge&logo=web3dotjs&logoColor=white)

### Languages & Frameworks
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)

### Infrastructure & Tools
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white) ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)

---

## Featured Projects

### Programmatic Payments & Settlement

**[x402 Migration Architecture](https://github.com/AllanMangeni/x402-migration-architecture-example)**
- Three-stage migration from Lithic webhook rails to native x402 on-chain settlement on Base
- Reduces state management from 15 lines to zero — SQLite schema, reconciliation logic, and webhook handler deleted entirely
- Live benchmarks via Toxiproxy network simulator under African 3G conditions

**[x402 Migration Sandbox](https://github.com/AllanMangeni/x402-migration-sandbox)**
- Head-to-head complexity comparison: legacy callback flow vs. autonomous x402 settlement
- Quantifies the 100% reduction in state management code when moving to programmable settlement
- Reference implementation for developers evaluating the migration path

### Protocol Infrastructure

**[Alusa](https://github.com/AllanMangeni/Alusa)**
- Parametric insurance protocol using agentic reasoning and the Stellar blockchain
- Automated claims triggered by verified on-chain events — no manual adjudication
- Built for real-world coverage scenarios in African markets

**[Akalysis](https://github.com/AllanMangeni/Akalysis)**
- Deployment cost and resource monitoring dashboard for the Akash decentralised compute network
- Tracks spend, node health, and resource allocation across deployments in real time

**[Lenderp2p](https://github.com/AllanMangeni/lenderp2p)**
- P2P lending platform that abstracts key financial data between lender and borrower
- On-chain loan origination with transparent risk disclosure

### Developer Tools

**[avoid-ai-writing](https://github.com/AllanMangeni/avoid-ai-writing)**
- Agent skill that audits and rewrites content to remove AI writing patterns
- Compatible with Claude Code, OpenCode, and Hermes
- Ships with heuristics for rhythm, sentence structure, and voice authenticity

---

## Writing

Top 2 Finance writer on HackerNoon. All pieces are grounded in implementation work.

**Programmatic Payments Series**

| Article | What it covers |
|---|---|
| [From Webhooks to x402](https://hackernoon.com/from-webhooks-to-x402-the-architectural-migration-equipping-autonomous-software-agents-for-the-agentic-economy) | The architectural case for dropping webhook-based payment rails and the complexity cost of legacy integrations |
| [Stress-Testing x402 on Emerging Market Infrastructure](https://hackernoon.com/the-architectural-migration-equipping-autonomous-software-agents) | Synchronous on-chain settlement under real low-connectivity conditions — latency data from Toxiproxy simulations |
| [The Idempotency Problem in African Cross-Border Settlement](https://hackernoon.com/u/allanmangeni) | Facilitator timeouts, the three-outcome ambiguity problem, and a recovery state machine for exactly-once delivery |
| [The Application Layer Is the Only Layer You Control](https://hackernoon.com/u/allanmangeni) | Why middleware, not the protocol, is where African deployment constraints get solved |

---

## GitHub Stats

| Stats | Streak | Top Languages |
|---|---|---|
| ![](https://github-readme-stats.vercel.app/api?username=AllanMangeni&theme=vue-dark&hide_border=false&include_all_commits=true&count_private=true) | ![](https://github-readme-streak-stats.herokuapp.com/?user=AllanMangeni&theme=vue-dark&hide_border=false) | ![](https://github-readme-stats.vercel.app/api/top-langs?username=AllanMangeni&theme=vue-dark&hide_border=false&include_all_commits=true&count_private=true&layout=compact) |

---

## Top Contributed Repos

![](https://github-contributor-stats.vercel.app/api?username=AllanMangeni&limit=5&theme=dark&combine_all_yearly_contributions=true)

---

[![](https://visitcount.itsvg.in/api?id=AllanMangeni&icon=0&color=0)](https://visitcount.itsvg.in)
