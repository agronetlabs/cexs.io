[![AI Co-Pilot: OpenClaw](https://img.shields.io/badge/AI%20Co--Pilot-OpenClaw-FF4500?style=for-the-badge&logo=github)](https://openclaw.ai)
[![ATF-AI Verified](https://img.shields.io/badge/ATF--AI-VERIFIED-2ea44f?style=for-the-badge)](https://github.com/agronetlabs/ATF-AI)
[![ERC-8040](https://img.shields.io/badge/ERC--8040-Compliant-0066ff?style=for-the-badge)](https://github.com/agronetlabs/erc-8040-ecosystem)
[![SWIFT ISO 20022](https://img.shields.io/badge/SWIFT-ISO%2020022-orange?style=for-the-badge)](https://www.iso20022.org/)
[![ISO 20022 Compatible](https://img.shields.io/badge/ISO%2020022-Compatible-00a651?style=for-the-badge)](https://www.iso20022.org/)
[![SWIFT Ready](https://img.shields.io/badge/SWIFT-Ready-ff6600?style=for-the-badge)](https://www.swift.com/)
[![PWA](https://img.shields.io/badge/PWA-Installable-purple?style=for-the-badge)](https://cexs.io)
[![Launch](https://img.shields.io/badge/Launch-Q2%202026-red?style=for-the-badge)](https://cexs.io)
[![Provenance Traceable](https://img.shields.io/badge/PROVENANCE-SIGNED-0f9d58?style=for-the-badge)](https://github.com/agronetlabs/ATF-AI)
[![GitHub Copilot](https://img.shields.io/badge/GitHub%20Copilot-Active-0066ff?style=for-the-badge&logo=githubcopilot)](https://github.com/features/copilot)
[![Build](https://img.shields.io/badge/build-passing-brightgreen?style=for-the-badge)](https://github.com/agronetlabs/backend)
[![Cloudflare](https://img.shields.io/badge/deployed-Cloudflare-F38020?style=for-the-badge&logo=cloudflare)](https://cloudflare.com)
![License](https://img.shields.io/badge/License-Proprietary-red?style=for-the-badge)

---

# CEXS.io — Institutional Digital Asset Exchange & Settlement Infrastructure

> Not just another exchange. A compliance-native settlement layer for the next generation of regulated digital assets.

---

## What is CEXS.io?

CEXS.io is an **institutional-grade digital asset exchange and settlement infrastructure** built natively on the [ATF-AI Autonomous Trust Framework](https://github.com/agronetlabs/ATF-AI).

---

## Core Architecture

```
+-----------------------------------------------------+
|                    CEXS.io PWA                       |
|         Installable -- No App Store Required         |
+------------------------+----------------------------+
                         |
+------------------------v----------------------------+
|              Settlement Engine (Rust/Axum)           |
|   +------------+  +-----------+  +---------------+  |
|   | TRON       |  | Ethereum  |  | CCTP Cross-   |  |
|   | Network    |  |           |  | Chain         |  |
|   +------------+  +-----------+  +---------------+  |
|              ATF-AI Audit Hash on every tx           |
+------------------------+----------------------------+
                         |
+------------------------v----------------------------+
|           ATF-AI Compliance Layer                    |
|   Zero-trust -- Cryptographic Provenance -- Audit    |
+------------------------+----------------------------+
                         |
+------------------------v----------------------------+
|           ERC-8040 Token Standard                    |
|   ESG Scoring -- SFDR 6/8/9 -- ISO 20022 -- SWIFT   |
+-----------------------------------------------------+
```

---

## Key Features

### Institutional-Grade
- Event-sourced architecture with complete audit trail
- Double-entry accounting -- cryptographically verifiable
- KYC/AML compliance ready
- Full regulatory reporting capabilities

### Real-Time Settlement
- Multi-chain: Ethereum, TRON, Base, Arbitrum
- Cross-Chain Transfer Protocol (CCTP) by Circle
- Stablecoin native: USDT, USDC
- ATF-AI audit hash on every transaction

### ESG & Compliance Native
- ERC-8040 -- first ESG token with SWIFT ISO 20022 support
- SFDR Article 6/8/9 automatic classification
- EU Taxonomy alignment calculation

### PWA -- No Gatekeepers
- Installable on iOS and Android directly from browser
- No App Store. No Play Store. No intermediaries.

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React 18 + TypeScript + Vite + Tailwind |
| Backend | Rust + Axum |
| Database | PostgreSQL + SQLx (double-entry ledger) |
| Blockchain | ethers-rs (Ethereum) + TRON + CCTP |
| Compliance | ATF-AI Protocol + ERC-8040 |
| Infrastructure | Supabase + Cloudflare |

---

## ATF-AI Integration

Every settlement generates an ATF-AI Audit Hash:

```
ATF-AI-AUDIT-{SHA256(token_id + stablecoin + amount + wallet_from + wallet_to)}
```

---

## Ecosystem

| Project | Description | Link |
|---------|-------------|------|
| ATF-AI | Autonomous Trust Framework | [github.com/agronetlabs/ATF-AI](https://github.com/agronetlabs/ATF-AI) |
| ERC-8040 | ESG Token Standard + SWIFT ISO 20022 | [github.com/agronetlabs/erc-8040-ecosystem](https://github.com/agronetlabs/erc-8040-ecosystem) |
| Backend | Settlement engine (Rust/Axum) | [github.com/agronetlabs/backend](https://github.com/agronetlabs/backend) |
| AgroNet Labs | Company | [agronet.ai](https://agronet.ai) |

---

## Roadmap

- [x] ATF-AI Protocol -- open spec published
- [x] ERC-8040 -- first ESG token with SWIFT ISO 20022 native support
- [x] Settlement engine -- Rust/Axum, multi-chain, live
- [x] PWA -- installable on iOS and Android
- [x] KYC/AML compliance architecture
- [ ] Q2 2026 -- Public launch
- [ ] Institutional onboarding

---

## Institutional Access

- Website: [cexs.io](https://cexs.io)
- Email: contact@cexs.io
- Demo: [calendly.com/admin-agronet/30min](https://calendly.com/admin-agronet/30min)
- Data Room: [agronet.ai/institucional](https://agronet.ai/institucional)

---

> This repository is the public institutional showcase of CEXS.io.
> The production codebase is maintained privately under AgroNet Labs LLC governance.

**AgroNet Labs LLC** | San Francisco | [agronet.ai](https://agronet.ai)
