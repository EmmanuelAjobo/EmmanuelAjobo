# Ajobo Emmanuel
**Fullstack Blockchain Engineer | Smart Contracts & Backend Infrastructure**

Lagos, Nigeria · Open to Remote & Relocation

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/emmanuel-ajobo)
[![Upwork](https://img.shields.io/badge/Upwork-6fda44?style=for-the-badge&logo=upwork&logoColor=white)](https://www.upwork.com/freelancers/~01c9b7162a904d6197?mp_source=share)
[![Code4rena](https://img.shields.io/badge/Code4rena-000000?style=for-the-badge&logo=ethereum&logoColor=white)](https://code4rena.com/@techdev)
[![Email](https://img.shields.io/badge/Email-ea4335?style=for-the-badge&logo=gmail&logoColor=white)](ajoboemmanuel04@gmail.com)

---

## Summary

Fullstack Blockchain Engineer with end-to-end ownership across smart contract architecture, backend blockchain infrastructure, and Web3 authentication. I build complete decentralized systems from gas-optimized Solidity contracts and DeFi protocol integrations to production-grade transaction services, event indexers, and wallet-based auth backends. Open to remote and relocation.

---

## Technical Skills

| Area | Technologies |
|------|-------------|
| Smart Contracts | Solidity, Yul, ERC-20/721/1155/4337, Foundry, Hardhat, OpenZeppelin, Slither |
| Backend | Node.js, TypeScript, Express.js, BullMQ, Redis, MongoDB, PostgreSQL, REST, WebSockets |
| Blockchain Infra | ethers.js v6, viem, The Graph, SIWE, RPC Management, MEV awareness |
| DeFi | Uniswap v2/v3, Aave, Flash Loans, AMM mechanics, Chainlink Oracles |
| Auth & Security | JWT, SIWE, Smart Contract Auditing, Reentrancy, Access Control, Signature Replay |
| Networks | Ethereum, Arbitrum, Optimism, Base, Polygon, Layer 2 rollup architecture |

---

## Projects

### VaultX : Multi-Round Presale & Vesting Protocol
`Solidity` `Foundry` `Hardhat` `OpenZeppelin` `Node.js` `ethers.js`

- Designed and deployed a full token sale system with tiered presale rounds (Pre-Seed, Seed, Public), Merkle-proof whitelisting, and cliff-plus-linear vesting, supporting a combined raise capacity of $5M across 3 investor tiers.
- Achieved sub-150k gas on the core `buyTokens()` function through storage packing and read optimization, cutting gas cost by 34% and saving investors an estimated $18,000 in fees at 40 gwei.
- Built an off-chain admin backend in Node.js and TypeScript to manage round configurations, generate Merkle proofs at scale, and monitor on-chain events in real time using ethers.js v6 listeners.

---

### TxManager : Production EVM Transaction Infrastructure
`Node.js` `TypeScript` `BullMQ` `Redis` `ethers.js v6` `Pino` `PostgreSQL`

- Built an end-to-end transaction lifecycle service covering submission, state tracking, stuck detection, dynamic gas bumping, rebroadcasting, and a dead letter queue for unrecoverable failures.
- Reduced stuck transaction rate by 94% over a 30-day load simulation by implementing a priority fee escalation algorithm tied to real-time mempool congestion signals from the RPC provider.
- Integrated structured Pino logging with Prometheus-compatible metrics, providing full observability across 12,000 test transactions and reducing mean time to diagnose failures from 40 minutes to under 5 minutes.

---

### DeFiShield : Lending Protocol with Integrated Audit
`Solidity` `Foundry` `Chainlink` `Slither` `Node.js` `The Graph`

- Architected a full collateralized lending protocol in Solidity with dynamic interest rate models, Chainlink oracle integration, and a liquidation engine supporting 4 collateral assets with 99.8% liquidation accuracy.
- Conducted a self-audit using Slither and manual review, identifying and remediating 2 high-severity issues including a price oracle manipulation vector and an unchecked return value in the repay function.
- Built a The Graph subgraph and Node.js query backend to index lending and liquidation events, reducing frontend data fetch latency by 65% compared to direct RPC polling.

---

## Experience

### Smart Contract Auditor
**Code4rena** · Competitive Audit Platform · `Jan 2024 — Present`

- Completed 8 competitive audits across DeFi, NFT, and governance protocols with combined TVL exceeding $18M.
- Identified 3 critical and 11 high-severity vulnerabilities, ranked top 20% in 3 consecutive contests.

### Freelance Blockchain Engineer
**Independent** · `Jan 2023 — Present`

- Delivered end-to-end blockchain systems for clients spanning smart contract development, backend infrastructure, and Web3 authentication.
- Maintained 90%+ test coverage and full API documentation across all 6 client projects delivered on time.

---

## Security & Auditing

- Competitive auditor on **Code4rena**
- Identified **3 critical** and **11 high-severity** vulnerabilities across DeFi, NFT, and governance protocols
- Audit focus: reentrancy, access control, flash loan surfaces, signature replay, storage collision
- Tooling: Slither, Aderyn, Foundry fuzz testing, manual review

---

## Education

**B.Eng Civil Engineering**
Federal University Oye-Ekiti · 2020 — 2026

---

*Available for Smart Contract Engineer, Backend Blockchain Engineer, and Security Auditor roles, remote or relocation-ready.*
