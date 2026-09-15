# Qora — Autonomous AI Business Partner for Paytm Merchants

> **Track 1:** Merchant Growth AI  
> **Team:** Quarders · team-DE3011461117 · PW IOI  
> **Stack:** Sarvam AI (Voice) + n8n (Automation) + Cognee (Memory)

## Live Demo
**[https://fursatiinsaan.github.io/Qora-AI/](https://fursatiinsaan.github.io/Qora-AI/)**

## What Qora Does
Qora turns every Paytm Soundbox into an intelligent business manager for India's 30M+ merchants.

### Core Capabilities
1. **Voice-First Vernacular Copilot** — Merchants speak in Hindi/any language via Sarvam AI. Ask "Aaj kitna galla aaya?" and get instant answers from Soundbox transaction data.
2. **Supplier Bill Audit Engine** — Automatically scans vendor invoices against contracted rates. Catches overcharges and flags vendor patterns via Cognee memory.
3. **Khata (Credit Ledger)** — Tracks customer credit, sends automated WhatsApp reminders via n8n workflows.
4. **Cashflow Forecasting & Sachet Micro-Credit** — Predicts cash position using Soundbox velocity. Pre-qualifies merchants for instant Paytm sachet loans.
5. **Smart Restocking** — Predicts stockouts from sales velocity, auto-drafts reorders to distributors.
6. **Festival Demand Prediction** — Cognee seasonal memory anticipates demand spikes before Navratri, Diwali, etc.

### Architecture
```
Merchant Voice (Sarvam) --> Qora Engine --> Cognee Memory Graph
                                       --> n8n Workflow Automation
                                       --> Paytm Soundbox + Lending APIs
```

## Run Locally
Open `index.html` in any browser.