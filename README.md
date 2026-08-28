# ⚡ Quotex OTC 24/7 Live REST API & WebSocket Streamer

> **Enterprise-grade, 24/7 self-healing REST API & WebSocket wrapper for Quotex (Real & OTC asset pairs).**  
> Designed to stream real-time price feeds, record closed M1/M5 candle histories, and power automated binary options trading bots and signal generators.

[![Telegram Direct](https://img.shields.io/badge/Contact-Telegram-blue?style=for-the-badge&logo=telegram)](https://t.me/YouKnowWho_am)
[![FastAPI](https://img.shields.io/badge/FastAPI-Docs_Live-009688?style=for-the-badge&logo=fastapi)](https://api1.api.cbtraderbd.xyz/docs)
[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python)](https://api1.api.cbtraderbd.xyz/docs)
[![License](https://img.shields.io/badge/License-Commercial_Source_Code-green?style=for-the-badge)](https://t.me/YouKnowWho_am)

---

## 🚀 Live API Interactive Documentation
Check all available live endpoints and test requests directly via our Swagger UI:  
👉 **[https://api1.api.cbtraderbd.xyz/docs](https://api1.api.cbtraderbd.xyz/docs)**

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
