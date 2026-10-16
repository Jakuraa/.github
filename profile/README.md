<div align="center">

# Jakuraa

**Corporate Technology Company — Established 2019**

*Building the software systems that enable AI agents and machines to discover, evaluate, access, meter, pay for, and settle digital services programmatically.*

[Corporate Website](https://jakuraa.com) • [Satelink Platform](https://satelink.network) • [Documentation](https://docs.satelink.network) • [Contact](mailto:hello@jakuraa.com)

</div>

---

Jakuraa Commercial Private Limited is an Indian technology corporation established in 2019 in Coimbatore, Tamil Nadu. We build software infrastructure for autonomous AI agents and automated systems to discover services, negotiate terms, and execute authorized machine-commerce workflows.

Our engineering scope spans AI-agent procurement infrastructure, API metering, programmatic payment rails (x402 on Base and USDT on Polygon), deterministic risk controls, and auditable on-chain settlement.

---

## Flagship Platform: Satelink

**[Satelink](https://satelink.network)** is our flagship platform: AI-agent and machine-commerce infrastructure.

Satelink's primary objective is agent procurement — helping software agents, automated systems, and developer teams discover, evaluate, authorize, access, meter, pay for, and settle supported digital services programmatically.

```
Discover → Evaluate → Authorize → Access → Meter → Pay → Settle
```

### Supported Platform Capabilities

1. **Machine Commerce & Service Discovery:** Public machine-readable service discovery catalogue at `/.well-known/satelink.json` and HTTP 402 payment specifications.
2. **Polygon PoS RPC Gateway:** High-performance, metered JSON-RPC capability at a flat $0.00003 per call.
3. **x402 Machine Payments:** HTTP-native, keyless pay-per-call micropayments in USDC on Base (`eip155:8453`).
4. **Prepaid Credit Metering:** Permissionless USDT deposits on Polygon PoS to verified on-chain vault contracts.
5. **Trading Intelligence API:** Metered analytical statistics (funding rates, open interest, liquidation clusters) returned per call.

### Platform Application: Satelink Trading AI (Paper Beta)

Satelink Trading AI is a specific application built on the Satelink platform.

- **Status:** Controlled paper-trading beta. Live execution is not available.
- **Safety Boundary:** AI proposes, deterministic risk engines and signed mandates decide. Capital remains at external regulated brokers; withdrawals are never enabled in code.

> **Operational Status:**  
> - **Platform & Payment Rails:** Live in production on Polygon PoS (137) and Base (8453).  
> - **Trading AI:** Controlled paper-trading beta; live execution is not yet available.  
> - **Node Operator Program:** Paused. Operator payouts are not active.

---

## Engineering Principles

- **Agent-First and API-First Architecture:** Every capability is exposed through well-documented, deterministic APIs and open protocols like MCP and HTTP 402, enabling direct machine consumption without friction.
- **AI Proposes, Deterministic Systems Decide:** Language models reason and contextualize. They never hold direct order placement execution tools, never manage credentials, and cannot modify risk thresholds or billing logic.
- **Mandatory Authorization:** High-impact execution requires explicit, authenticated user mandates.
- **Zero Custody:** User capital resides entirely with external regulated brokers or user wallets. Satelink never holds customer deposits, and autonomous withdrawal capabilities are disabled in code.
- **No Unverified Claims:** All documentation, metrics, and capabilities reflect ground truth. We make zero financial return or outperformance claims.
- **Auditable & Reconcilable Settlement:** Every settled transaction reconciles on-chain with cryptographic certainty.
- **Open Standards:** We build upon and contribute to public standards including HTTP 402 specifications and the Model Context Protocol (MCP).

---

## Open Source & Core Repositories

- **[`Jakuraa/Satelink_Network`](https://github.com/Jakuraa/Satelink_Network)**  
  The core monorepo for the Satelink platform: machine-commerce infrastructure, Polygon RPC gateway, metering, web application, and Trading AI copilot.
- **[`Jakuraa/x402-kit`](https://github.com/Jakuraa/x402-kit)**  
  Standalone, MIT-licensed Express middleware for HTTP 402 micropayments in USDC on Base.
- **[`Jakuraa/contracts`](https://github.com/Jakuraa/contracts)**  
  Solidity smart contracts for on-chain usage settlement and credit vaults on Polygon PoS.

### Verifiable On-Chain Contracts

| Contract | Network | Verified Address |
|:---|:---|:---|
| **RevenueVaultV2** (Credit Deposits) | Polygon Mainnet (`137`) | [`0x577D3716d6Ad5b676d230f5409deF9838FABaCEF`](https://polygonscan.com/address/0x577D3716d6Ad5b676d230f5409deF9838FABaCEF) |
| **USDT Contract** | Polygon Mainnet (`137`) | [`0xc2132D05D31c914a87C6611C10748AEb04B58e8F`](https://polygonscan.com/address/0xc2132D05D31c914a87C6611C10748AEb04B58e8F) |
| **Treasury / x402 Payee** | Base (`8453`) / Polygon (`137`) | [`0x966E1Ae22996545015b1414B35234b10719d7Ad4`](https://basescan.org/address/0x966E1Ae22996545015b1414B35234b10719d7Ad4) |

---

## Corporate Governance & Verification

Jakuraa Commercial Private Limited is an Indian corporation registered under the Companies Act, 2013.

- **Corporate Identity Number (CIN):** `U51909TZ2019PTC031777`
- **Incorporation Date:** 4 December 2019
- **Registered Jurisdiction:** Coimbatore, Tamil Nadu, India
- **GSTIN:** `33AADCF9341B1Z1`
- **DGFT Import-Exporter Code (IEC):** `AADCF9341B`
- **Udyam Registration:** `UDYAM-TN-03-0082507`

---

## Verified Contact & Channels

- **Corporate Website:** [https://jakuraa.com](https://jakuraa.com)
- **Satelink Platform:** [https://satelink.network](https://satelink.network)
- **Documentation:** [https://docs.satelink.network](https://docs.satelink.network)
- **Public Infrastructure RPC:** `https://rpc.satelink.network`
- **General Inquiries:** [hello@jakuraa.com](mailto:hello@jakuraa.com)
- **Product Inquiries:** [press@satelink.network](mailto:press@satelink.network)

---

<div align="center">
  <sub>© 2019–2026 Jakuraa Commercial Private Limited. All rights reserved. Satelink is the flagship platform of Jakuraa Commercial Private Limited.</sub>
</div>
