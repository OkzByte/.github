<div align="center">

# 🌐 OkzByte Ecosystem

### The World's Most Advanced Hybrid Exchange & Tokenized RWA Marketplace

![OkzByte Platform](https://img.shields.io/badge/Exchange-Institutional%20Grade-f0b90b?style=for-the-badge)
![RWA Platform](https://img.shields.io/badge/RWA-Real%20Estate%20%26%20Land%20Bonds-0ecb81?style=for-the-badge)
![Protocol](https://img.shields.io/badge/Protocol-OKBOND%20Polygon-8247e5?style=for-the-badge)
![Stack](https://img.shields.io/badge/Monorepo-48.9K%20Lines%20TypeScript-blue?style=for-the-badge)

<p align="center">
  <b>Trading Engine</b> • <b>Tokenized Real Estate</b> • <b>Rent & Installments</b> • <b>Service Providers Portal</b>
</p>

---

</div>

## 🚀 About OkzByte

**OkzByte** goes beyond conventional crypto exchanges. It is a massive, unified **Financial Infrastructure & Real-World Asset (RWA) Marketplace** bridging institutional Web3 liquid asset trading with tokenized physical real estate, commercial land bonds, and fractional asset ownership.

The flagship product — **Orakzai Properties** — is a production-grade **Exchange + Marketplace** hybrid: **43+ screens**, a **full order-matching trading engine**, an **Express 5 API with 60+ endpoints**, and a **PostgreSQL data layer with 21 schema modules**, all written in modern TypeScript across a pnpm monorepo (~48,900 lines).

---

## 🏛️ Core Platform Capabilities

### 1. 🏢 All-in-One Real Estate & Asset Marketplace

* **Buy & Sell:** On-chain full and fractional property ownership (`Browse`, `PropertyDetail`, `PostProperty`, `MyProperties`)
* **Rent & Booking:** Smart contract-driven short-term property bookings and long-term lease management (`Bookings`)
* **Installment Engine:** Structured, flexible milestone-based property acquisition plans (`InvestPortal`, `InvestDetail`)
* **Service Provider Gateway:** Dedicated portal for real estate developers, brokers, property managers, and legal services (`Services`)
* **Lead Management CRM:** Property leads, call logs and chat with agents (`AgentDashboard`, `Inbox`, `ChatRoom`)
* **Flagship Projects:** Azan Smart City and curated investment projects (`Projects`, `AzanSmartCity`)

### 2. ⚡ Next-Gen Trading & Wealth Infrastructure

* **Order-Matching Engine:** Real price-time priority matching with **0.5% trading fee**, order book, tickers, candles and price history (`orderMatcher`)
* **Live Trading Floor:** Streaming order books and positions via Server-Sent Events (`TradingFloor`, `Markets`, `Trade`)
* **Spot & P2P Exchange:** Order placement, my-orders management and P2P settlement with escrow (`P2P`, `Trades`)
* **AI Bot Trading:** Automated quantitative bots, grid trading, and intelligent portfolio balancing
* **RWA Staking Vaults:** High-yield vaults backed by prime real estate properties (e.g., DHAISB, ASC Smart Center, Commercial Land Notes) (`RwaStaking`)
* **Launchpad:** Dual-mode token allocation via **OKZ Subscriptions** and **Verifiable On-Chain USDT Lotteries** (`Launchpad`)
* **OKBOND DeFi Framework:** Decentralized yield protocol and liquidity vault framework running on Polygon

### 3. 💳 OkzByte Pay — Banking-Grade Wallet & Payments

* **OkzByte Pay Send & Receive:** Instant peer-to-peer money transfers (`OkzBytePaySend`, `OkzBytePayReceive`)
* **Crypto Deposit & Withdrawal:** Full crypto on-ramp/off-ramp flows with detailed transaction receipts (`CryptoDepositFlow`, `CryptoWithdrawFlow`, `DepositDetail`)
* **Transaction Ledger:** Complete wallets, transactions and receipts ledger with real-time streaming
* **PIN Security:** Wallet-level 4-digit PIN set/verify protection (`wallet/set-pin`, `wallet/verify-pin`)

### 4. 🔐 Identity, Compliance & Governance

* **KYC Verification:** Complete KYC onboarding gate with admin review (`KYC`, `KYCGateModal`, `AdminKYC`)
* **Admin Panel:** Full governance suite — platform configuration, KYC review, user oversight (`AdminPanel`, `AdminConfig`)
* **Subscriptions & Plans:** Tiered listing and platform subscription system (`Pricing`, `Subscribe`)
* **Notifications:** Push subscription, price alerts and notification settings (`PriceAlerts`, `NotificationSettings`, `Notifications`)

---

## 📊 Platform by the Numbers

| Metric | Value |
|---|---|
| Frontend screens | 43+ pages (React 19 · Vite 7 · Tailwind 4) |
| API endpoints | 60+ REST endpoints (Express 5) |
| Database schema | 21 PostgreSQL tables (Drizzle ORM) |
| Codebase | ~48,900 lines of TypeScript (pnpm monorepo) |
| Real-time layer | SSE streaming: order books, trades, wallet events |
| Trading | Order-matching engine, 0.5% fee, order book, candles |
| Validation | Zod (OpenAPI-driven codegen) |
| Auth | Session + Clerk proxy middleware |

### Frontend — All Modules

`Home` · `Browse` · `PropertyDetail` · `PostProperty` · `MyProperties` · `InvestPortal` · `InvestDetail` · `Projects` · `AzanSmartCity` · `RwaStaking` · `Portfolio` · `TradingPortfolio` · `TradingFloor` · `Trade` · `Trades` · `Markets` · `P2P` · `Wallet` · `OkzBytePaySend` · `OkzBytePayReceive` · `CryptoDepositFlow` · `CryptoWithdrawFlow` · `DepositDetail` · `Launchpad` · `KYC` · `AgentDashboard` · `Services` · `Inbox` · `ChatRoom` · `Notifications` · `PriceAlerts` · `AdminPanel` · `AdminKYC` · `AdminConfig` · `Pricing` · `Subscribe` · `Profile` · `ProfileCenter` · `Feedback` · `Auth`

### Backend — All Modules

| Module | Responsibility |
|---|---|
| `properties` | Listings, stats, ownership CRUD |
| `trading` | Order book, ticker, candles, price history, orders, SSE stream |
| `wallet` | Balances, deposits, withdrawals, transfers, receipts, PIN, SSE stream |
| `investment-projects` | Projects, updates, fractional investing |
| `portfolio` | Portfolio dashboard and positions |
| `projects` / `bookings` | Projects, updates and property bookings |
| `agent` | Agent dashboard, profile, leads, messages, call logs |
| `leads` / `notifications` | Lead CRM and push notification engine |
| `subscription` | Plans, subscribe/cancel, listing counts |
| `orderMatcher` | Price-time priority matching with fee ledger |

---

## 🛠️ Tech Stack & Ecosystem

- **Blockchain:** Polygon Protocol, Solidity Smart Contracts, ERC-20 / ERC-721 / ERC-1155 Token Standards
- **Frontend / Mobile:** React 19, Tailwind CSS 4, Framer Motion, TanStack Query, Native Mobile PWA / Web App
- **Backend Infrastructure:** Express 5 API Servers, Node.js 24, WebSockets/SSE, PostgreSQL + Drizzle ORM, Zod validation, Orval OpenAPI codegen
- **Architecture:** pnpm workspaces monorepo (`api-server`, `orakzai-properties`, `api-client-react`, `api-spec`, `api-zod`, `db` libs), TypeScript 5.9, strict typechecking, CI-ready build pipeline

---

## 🌐 Official Channels & Links

- 🌐 **Web App Platform:** [https://orakzai-properties-api-server.vercel.app](https://orakzai-properties-api-server.vercel.app)
- 💻 **Source Repository:** [faisalorakzai-lab/Orakzai-Properties](https://github.com/faisalorakzai-lab/Orakzai-Properties)
- 📧 **Official Support:** info@orakzaibond.com
- 🏢 **Organization:** Orakzai Group

---

<div align="center">
  <sub>© OkzByte Ecosystem. Building the future of Web3 Finance & Real-World Infrastructure.</sub>
</div>
