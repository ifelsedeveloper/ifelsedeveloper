# Vadim Fadeev — Blockchain Tech Lead / Senior Smart‑Contract Engineer @ 1inch

Hi, I’m **Vadim** (aka **@ifelsedeveloper**) — I build end‑to‑end blockchain products: smart contracts, indexing backends, and modern front‑ends. I’ve led and shipped NFT marketplaces, DEXes, and tooling across **Ethereum**, **Solana**, and **Aptos**. I enjoy clean architectures, deterministic deployments, and squeezing gas like it’s a sport. Now at **1inch**, I design DEX execution (**SwapVM** / **Aqua**) and a custom AMM backed by publication‑grade formal mathematics and formal verification.

<p align="center">
  <a href="https://github.com/ifelsedeveloper"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ifelsedeveloper?label=Follow&style=for-the-badge"></a>
  <a href="https://www.linkedin.com/in/vadim-fadeev/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-vadim--fadeev-blue?style=for-the-badge&logo=linkedin"></a>
  <a href="mailto:xboxfadeev@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Contact-Email-success?style=for-the-badge&logo=gmail"></a>
</p>

---

## 🚀 What I’m building now
- **1inch — SwapVM & Aqua** — VM‑based DEX execution architecture + its liquidity integration layer; a custom two‑layer AMM with bonding curves backed by formal whitepaper/yellowpaper. AMM compensation math through analytical verification before external audit; owned the audit process end‑to‑end.
- **RARI cross‑chain bridge (LayerZero OFT)** — Ethereum ↔ Base: contracts, adapter, and a minimal NestJS microservice (`lz-bridge-service`) plus a Next.js UI (`ui-rari-bridge`).
- **Reward swap / liquidity automation** — NestJS service integrating **Uniswap v3/v4** (AlphaRouter/QuoterV2) for scheduled swaps and cron‑driven flows.
- **Gas‑efficient Solidity patterns** — storage packing, memory‑safe assembly, proxy patterns, CREATE2/CREATE3 deterministic deploys.

> I love turning messy multi‑chain flows into simple, reliable CLIs and services.

---

## 🧩 Selected work
- **Custom AMM/DEX (1inch)** — AMM with analytical verification of the Solidity implementation against its mathematical model.
- **Rarible** — Tech lead & smart‑contract engineer for EVM/Solana/Aptos: primary sales, marketplace, indexers, and UI SDK packages.
- **DEX (EVM)** — Designed and delivered core contracts and The Graph APIs for a farming DEX (SwapTasteNFT - UniswapV2).
- **Minter Browser / Blockmint** — Architected data‑heavy pipelines, CI/CD, and crypto monetization flows.
- **Tradespoon / HFT tools** — Market‑data pipelines and forecasting (CBOE/CME protocols), mobile apps, and analytics.

> Conferences & community: NFT Paris, NFT Lisbon (2022–2025), Web Summit 2018/2023, Paris Blockchain Week 2024, DevCon Bangkok 2024, multiple meetups & hackathons.

---

## 🛠️ Tech stack (favorite tools)
**Chains:** Ethereum, Solana, Aptos · **Core:** Solidity, Rust, Move, TypeScript, Python  
**Contracts:** Foundry, Hardhat, Anchor, OpenZeppelin · ERC‑20/721/1155, ERC‑4626, ERC‑2612 / Permit2, EIP‑712, ERC‑1967 / UUPS  
**Math:** Newton‑Raphson, bisection / binary search, modular & finite‑field arithmetic, extended Euclidean, Chinese Remainder Theorem, fixed‑point arithmetic, numerical verification (Python)  
**Infra:** NestJS, The Graph, Postgres, Redis, MongoDB, IPFS  
**DevOps:** GitHub Actions, Docker, CI/CD, Terraform · **Patterns:** proxies, upgradeability, deterministic deploys  
**Data/Trading:** Uniswap v3, market‑data processing, backtesting, automation

<p>
  <img src="https://img.shields.io/badge/Solidity-363636?logo=solidity&logoColor=white"> 
  <img src="https://img.shields.io/badge/Foundry-black">
  <img src="https://img.shields.io/badge/Hardhat-181717?logo=hardhat">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white">
  <img src="https://img.shields.io/badge/NestJS-EA2845?logo=nestjs&logoColor=white">
  <img src="https://img.shields.io/badge/The%20Graph-6747ED?logo=thegraph&logoColor=white">
  <img src="https://img.shields.io/badge/Postgres-316192?logo=postgresql&logoColor=white">
  <img src="https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white">
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white">
</p>

---

## 🧪 Highlighted projects
- **1inch — DEX execution & custom AMM** — VM‑based DEX execution and liquidity‑integration layer; a custom AMM with **formally verified invariants** and end‑to‑end **audit‑by‑design** ownership; cross‑chain resolver work and **Fusion+** integration.  
- **LayerZero RARI OFT bridge** — OFT token + **Adapter** on Ethereum, service (`lz-bridge-service`) and **UI** (`ui-rari-bridge`) for seamless ETH→Base transfers.  
- **Reward Swap Service** — Cron‑driven swaps (WETH⇄RARI) with slippage controls and environment‑driven configs.  
- **Indexers & APIs** — The Graph endpoints for DEX/NFT flows; infra & CI/CD from zero to production.  
- **Marketplace & primary sales** — Multi‑chain smart contracts and SDKs for integrating NFT primitives into apps.

> If you want a secure marketplace, a deterministic deploy pipeline, or a simple bridge UI that *just works*, that’s my jam.

---

## 🧭 Experience
- **1inch, Senior Smart‑Contract Engineer** — *Nov 2025 → Present*  
- **Rarible, Tech Lead / Senior Blockchain Developer** — *Sep 2022 → Nov 2025*  
- **Blockmint Technologies, Tech Lead / Senior Software Architect** — *Jun 2017 → Jul 2023*  
- **Velvetech LLC, Tech Lead / Senior Software Engineer** — *Dec 2012 → Sep 2022*  

**Education:** M.Sc. & B.Sc. in Applied Mathematics & Computer Science — Novosibirsk State Technical University

---

## 📄 Publications
- **Reinvested strict additivity for two curves** — formal proof for custom AMM mathematics (1inch SwapVM). [PDF](https://github.com/1inch/swap-vm/blob/99dcb481724af1e0fd5d0da41e00a34698b6d1ec/docs/reinvested_strict_additivity_two_curves.pdf)

---

## 🔗 Useful links
- 1inch — https://1inch.com/ 
- Rarible — https://rarible.com/  
- Xayo — https://www.xayoapp.com/  
- Carbon Tokens Market — https://carbontokensmarket.com/  
- Minter Browser — http://www.getminter.com  
- Tradespoon — http://www.tradespoon.com  

---

## 📫 Reach me
- Email: **xboxfadeev@gmail.com**
- LinkedIn: **https://www.linkedin.com/in/vadim-fadeev/**
- GitHub: **https://github.com/ifelsedeveloper**

If you’re building onchain infra (marketplaces, bridges, indexers, or clever trading tools), let’s talk.

---

### 📈 GitHub stats
> These images are generated by community services.

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=ifelsedeveloper&show_icons=true)

---

<sub>Last updated: June 2, 2026</sub>
