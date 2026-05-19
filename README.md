[![AI Co-Pilot: OpenClaw](https://img.shields.io/badge/AI%20Co--Pilot-OpenClaw-FF4500?style=for-the-badge&logo=github)](https://openclaw.ai)
# CEXS.io â€” Institutional Digital Asset Exchange & Settlement Infrastructure

[![ATF-AI Verified](https://img.shields.io/badge/ATF--AI-VERIFIED-2ea44f?style=for-the-badge)](https://github.com/agronetlabs/ATF-AI)
[![ERC-8040](https://img.shields.io/badge/ERC--8040-Compliant-0066ff?style=for-the-badge)](https://github.com/agronetlabs/erc-8040-ecosystem)
[![SWIFT ISO 20022](https://img.shields.io/badge/SWIFT-ISO%2020022-orange?style=for-the-badge)]()
[![PWA](https://img.shields.io/badge/PWA-Installable-purple?style=for-the-badge)]()
[![Launch](https://img.shields.io/badge/Launch-Q2%202026-red?style=for-the-badge)]()

---

<div align="center">
  <img src="assets/banner.png" alt="CEXS.io" width="100%">
</div>

---

## What is CEXS.io?

CEXS.io is an **institutional-grade digital asset exchange and settlement infrastructure** â€” built natively on the [ATF-AI Autonomous Trust Framework](https://github.com/agronetlabs/ATF-AI).

> Not just another exchange. A compliance-native settlement layer for the next generation of regulated digital assets.

---

## Core Architecture

```
â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”
â”‚                    CEXS.io PWA                       â”‚
â”‚         Installable â€” No App Store Required          â”‚
â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”¬â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜
                     â”‚
â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â–¼â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”
â”‚              Settlement Engine (Rust/Axum)           â”‚
â”‚   â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”¬â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”¬â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â” â”‚
â”‚   â”‚ TRON Network â”‚ Ethereum     â”‚ CCTP Cross-Chain â”‚ â”‚
â”‚   â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”´â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”´â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜ â”‚
â”‚              ATF-AI Audit Hash on every tx           â”‚
â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”¬â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜
                     â”‚
â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â–¼â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”
â”‚           ATF-AI Compliance Layer                    â”‚
â”‚   Zero-trust Â· Cryptographic Provenance Â· Auditable  â”‚
â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”¬â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜
                     â”‚
â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â–¼â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”
â”‚           ERC-8040 Token Standard                    â”‚
â”‚   ESG Scoring Â· SFDR Articles 6/8/9 Â· ISO 20022     â”‚
â”‚   EU Taxonomy Â· SWIFT Bridge Â· Multi-chain           â”‚
â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜
```

---

## Key Features

### ðŸ›ï¸ Institutional-Grade
- Event-sourced architecture with complete audit trail
- Double-entry accounting â€” cryptographically verifiable
- KYC/AML compliance ready
- Full regulatory reporting capabilities

### âš¡ Real-Time Settlement
- Multi-chain settlement: Ethereum, TRON, Base, Arbitrum
- Cross-Chain Transfer Protocol (CCTP) by Circle
- Stablecoin native: USDT, USDC
- ATF-AI audit hash embedded in every transaction

### ðŸŒ± ESG & Compliance Native
- ERC-8040 token standard â€” first ESG token with SWIFT ISO 20022 support
- SFDR Article 6/8/9 automatic classification
- EU Taxonomy alignment calculation
- Carbon intensity estimation

### ðŸ“± PWA â€” No Gatekeepers
- Installable on iOS and Android directly from browser
- No App Store. No Play Store. No intermediaries.
- Full native experience â€” offline capability, push notifications

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React 18 + TypeScript + Vite + Tailwind |
| Backend | Rust + Axum (high-performance async) |
| Database | PostgreSQL + SQLx (double-entry ledger) |
| Blockchain | ethers-rs (Ethereum) + TRON + CCTP |
| Compliance | ATF-AI Protocol + ERC-8040 |
| Infrastructure | Supabase + Cloudflare |

---

## ATF-AI Integration

Every settlement operation on CEXS.io generates an **ATF-AI Audit Hash**:

```
ATF-AI-AUDIT-{SHA256(token_id + stablecoin + amount + wallet_from + wallet_to)}
```

This hash is traceable back to the full ATF-AI provenance chain â€” connecting every on-chain settlement to its compliance attestation. Any auditor can verify the complete chain from SWIFT message to on-chain transaction.

---

## Ecosystem

| Project | Description | Link |
|---------|-------------|------|
| **ATF-AI** | Autonomous Trust Framework â€” governance protocol | [github.com/agronetlabs/ATF-AI](https://github.com/agronetlabs/ATF-AI) |
| **ERC-8040** | ESG Token Standard + SWIFT ISO 20022 bridge | [github.com/agronetlabs/erc-8040-ecosystem](https://github.com/agronetlabs/erc-8040-ecosystem) |
| **AgroNet Backend** | Settlement engine (Rust/Axum) | [github.com/agronetlabs/backend](https://github.com/agronetlabs/backend) |
| **AgroNet Labs** | Company | [agronet.ai](https://agronet.ai) |

---

## Roadmap

- [x] ATF-AI Protocol â€” open spec published
- [x] ERC-8040 â€” first ESG token with SWIFT ISO 20022 native support
- [x] Settlement engine â€” Rust/Axum, multi-chain, live
- [x] PWA â€” installable on iOS and Android
- [x] KYC/AML compliance architecture
- [ ] **Q2 2026 â€” Public launch**
- [ ] Institutional onboarding
- [ ] Regulated markets integration

---

## Institutional Access

For institutional inquiries, partnerships, or investor relations:

ðŸŒ [cexs.io](https://cexs.io)
ðŸ“© contact@cexs.io
ðŸ“… [Schedule a demo](https://calendly.com/admin-agronet/30min)

---

> This repository is the public institutional showcase of CEXS.io.
> The production codebase is maintained privately under AgroNet Labs LLC governance.

**AgroNet Labs LLC** | San Francisco | [agronet.ai](https://agronet.ai)

