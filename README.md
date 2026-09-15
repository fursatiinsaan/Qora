# Qora — Autonomous AI Business Partner for Paytm Merchants

> **Track 1:** Merchant Growth AI  
> **Stack:** Sarvam AI (Voice) + n8n (Automation) + Cognee (Memory)

## Live Demo
**[https://fursatiinsaan.github.io/Qora/](https://fursatiinsaan.github.io/Qora/)**

## What Qora Does
Qora turns every Paytm Soundbox into an intelligent business manager for India's 30M+ merchants.

### Core Capabilities
1. **Voice-First Vernacular Copilot** — Merchants speak in Hindi/any language via Sarvam AI.
2. **Supplier Bill Audit Engine** — Scans vendor invoices against contracted rates. Catches overcharges via Cognee memory.
3. **Khata (Credit Ledger)** — Tracks customer credit, sends WhatsApp reminders via n8n.
4. **Cashflow Forecasting & Sachet Micro-Credit** — Predicts cash position, pre-qualifies for Paytm sachet loans.
5. **Smart Restocking** — Predicts stockouts, auto-drafts reorders.
6. **Festival Demand Prediction** — Cognee seasonal memory anticipates demand spikes.

### Architecture
```
Merchant Voice (Sarvam) --> Qora Engine --> Cognee Memory Graph
                                       --> n8n Workflow Automation
                                       --> Paytm Soundbox + Lending APIs
```

## Run Locally
Open `index.html` in any browser.