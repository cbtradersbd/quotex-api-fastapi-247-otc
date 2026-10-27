# ⚡ Quotex OTC 24/7 Live REST API & Reverse-Engineered Binary Stream Gateway

> **Enterprise-grade, 24/7 self-healing REST API & Proprietary Reverse-Engineered Binary Protocol Engine for Quotex (Real & OTC asset pairs).**  
> Designed to stream real-time price feeds, record closed M1/M5 candle histories, and power automated binary options trading bots and signal generators.

[![Telegram Direct](https://img.shields.io/badge/Contact-Telegram-blue?style=for-the-badge&logo=telegram)](https://t.me/YouKnowWho_am)
[![FastAPI](https://img.shields.io/badge/FastAPI-Docs_Live-009688?style=for-the-badge&logo=fastapi)](https://api1.api.cbtradersbd.com/docs)
[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python)](https://api1.api.cbtradersbd.com/docs)
[![License](https://img.shields.io/badge/License-Commercial_Source_Code-green?style=for-the-badge)](https://t.me/YouKnowWho_am)

---

## 🚀 Live API Interactive Documentation
Check all available live endpoints and test requests directly via our Swagger UI:  
👉 **[https://api1.api.cbtradersbd.com/docs](https://api1.api.cbtradersbd.com/docs)**

---

## ✨ Key System Features

- 🕒 **Configurable M1 Candle History**: Automatically maintains a rolling historical database of closed M1 candles for all active Real & OTC asset pairs.
- 🚫 **Anti-Repaint Guarantee**: Only finalized, closed candles are saved to the database. Running candles are ignored to eliminate signal repainting.
- 💰 **Historical Payout Rate Tracking**: Every candle entry stores the exact real-time payout percentage recorded at that specific minute.
- 🕒 **Fully Configurable Timezone Support**: All API JSON outputs format timestamps as `YYYY-MM-DD HH:MM:SS` with fully customizable timezone offsets (UTC, UTC+6, EST, IST, GMT, etc.).
- 🔄 **Dynamic 24/7 Asset Discovery**: Automatically detects active markets (switching seamlessly between weekday forex and weekend OTC pairs) without requiring server restarts.
- 🛡️ **Bulletproof Self-Healing Architecture**:
  - Automatically reconnects during network drops or socket disconnections.
  - Automatically refreshes session tokens and manages Cloudflare clearance.
  - Automatically detects offline downtime gaps and backfills missing candles.

---

## 📡 Available API Endpoints

| Endpoint | Method | Description |
| :--- | :--- | :--- |
| `/docs` | `GET` | Interactive Swagger API documentation |
| `/api/quotex/live-price` | `GET` | Get real-time price & tick stream for any pair |
| `/api/quotex/candles` | `GET` | Fetch multi-timeframe historical OHLCV data |
| `/api/quotex/payouts` | `GET` | Retrieve live payout rates across all pairs |
| `/api/quotex/signals` | `POST` | Execute or generate automated trading signals |

---

## 🛒 Commercial License & Purchase Source Code

Looking for the full, production-ready source code with complete rights and 1-on-1 developer support?

### What’s Included in the Full Package:
- 📦 **100% Full Unlocked Source Code** (`app.py`, `worker.py`, `database.py`, `pyquotex/` engine).
- 🚀 **1-Click Automated Windows & Linux VPS Launcher**.
- ⚡ **Unlimited Personal & Commercial License** (Deploy on unlimited VPS/servers).
- 🛠️ **24/7 Developer Support & Setup Assistance**.
- 🔄 **Lifetime Code Updates & Bug Fixes**.

📩 **Contact on Telegram to Buy**: [@YouKnowWho_am](https://t.me/YouKnowWho_am)  
💳 **Accepted Payment Methods**: USDT (TRC20/BEP20), Binance Pay, Crypto, Local Mobile Banking.

---

## 🌐 CB Traders BD Ecosystem : Explore All Broker APIs & Bots

Cross-platform algorithmic trading tools, real-time Decrypted Sub-Millisecond Binary Feeds, and AI signal engines:

| Platform | Official Official High-Frequency Binary Protocol & REST API | Signals & Telegram Bots | Data Tools & Bridges |
| :--- | :--- | :--- | :--- |
| **Quotex** | [Quotex-API](https://github.com/cbtradersbd/Quotex-API) | [quotex-otc-signal-engine](https://github.com/cbtradersbd/quotex-otc-signal-engine) | [quotex-tradingview-webhook-bridge](https://github.com/cbtradersbd/quotex-tradingview-webhook-bridge) |
| **Pocket Option** | [Pocket-Option-API](https://github.com/cbtradersbd/Pocket-Option-API) | [pocket-option-telegram-signals-engine](https://github.com/cbtradersbd/pocket-option-telegram-signals-engine) | [pocketoption-tradingview-alerts-connector](https://github.com/cbtradersbd/pocketoption-tradingview-alerts-connector) |
| **IQ Option** | [IQ-Option-API](https://github.com/cbtradersbd/IQ-Option-API) | [iq-option-telegram-signal-bot](https://github.com/cbtradersbd/iq-option-telegram-signal-bot) | [iq-option-market-data-api](https://github.com/cbtradersbd/iq-option-market-data-api) |
| **Binolla** | [Binolla-API](https://github.com/cbtradersbd/Binolla-API) | [binolla-live-signals-bot](https://github.com/cbtradersbd/binolla-live-signals-bot) | [binolla-tradingview-webhook-bot](https://github.com/cbtradersbd/binolla-tradingview-webhook-bot) |

---

## ❓ Frequently Asked Questions (FAQ)

<details>
<summary><b>1. How do I get started and connect to the live API endpoints?</b></summary>
Explore interactive Swagger documentation, test live endpoints, and inspect schemas directly at <a href="https://api1.api.cbtradersbd.com/docs">https://api1.api.cbtradersbd.com/docs</a>. Clone this repository, install dependencies with <code>pip install -r requirements.txt</code>, and configure credentials in <code>.env</code>.
</details>

<details>
<summary><b>2. Are 24/7 OTC asset pairs supported for continuous trading?</b></summary>
Yes! Our systems provide continuous round-the-clock streaming for OTC asset pairs alongside standard financial currency pairs with real-time candlestick feeds and low-latency execution.
</details>

<details>
<summary><b>3. Can I automate binary options trades directly from TradingView alerts?</b></summary>
Yes! Our TradingView webhook bridges convert Pine Script alert webhooks into instant automated trade executions with customizable risk management, martingale, and stop-loss rules.
</details>

<details>
<summary><b>4. How do the copy trading bridge and signal engines work?</b></summary>
The copy trading bridge mirrors trades from master accounts to target accounts with zero latency. The signal engines utilize non-repaint technical indicators and volatility filters to dispatch high-accuracy alerts to Telegram or webhook endpoints.
</details>

---

## 🏷️ Search & Discovery Keywords
`quotex-api` • `pocket-option-api` • `iq-option-api` • `binolla-api` • `binary-options-bot` • `algorithmic-trading` • `tradingview-webhook-bridge` • `247-otc-market-data` • `fastapi-binary-stream` • `copy-trading-bot` • `automated-trading-python` • `live-payout-monitor`

---

## ⭐ Star This Project
If this toolkit assisted your algorithmic trading research or bot deployment, please give it a **Star on GitHub** to support active open-source development and help other traders find it!
<!-- last_verified_sync: 1793078528 -->
