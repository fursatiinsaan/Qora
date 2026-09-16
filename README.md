# Qora — Autonomous AI Business Partner for Paytm Merchants

> **Track 1:** Merchant Growth AI — Build the AI business partner for every Paytm merchant  
> **Stack:** Sarvam AI (Voice) + n8n (Automation) + Cognee (Memory)

## Live Demo
**[https://fursatiinsaan.github.io/Qora/](https://fursatiinsaan.github.io/Qora/)**

---

## The Problem
India's 30M+ small merchants manage their businesses with mental math, paper khatas, and WhatsApp messages. They lose money to supplier overcharges, missed credit collections, stockouts, and cashflow gaps — problems that scale with business growth.

## What Qora Does
Qora turns every Paytm AI Soundbox into an intelligent business co-pilot that speaks the merchant's language.

### Core Capabilities
| Feature | How It Works | Tech |
|---|---|---|
| **Voice-First Copilot** | Merchant asks "Aaj kitna galla aaya?" in Hindi/Tamil/Kannada — gets instant answer from Soundbox data | Sarvam Saaras v4 STT + TTS (22+ Indic languages) |
| **Supplier Bill Audit** | WhatsApp invoice images auto-scanned, line items extracted, rates cross-checked against contracted prices | n8n OCR workflow + Cognee rate memory |
| **Khata Management** | Tracks customer credit, auto-sends vernacular WhatsApp reminders when overdue | Cognee customer graph + n8n WhatsApp API |
| **Cashflow Forecasting** | Predicts cash position from Soundbox velocity, pre-qualifies for Paytm sachet micro-loans | Cognee temporal analysis |
| **Smart Restocking** | Detects sales velocity spikes, predicts stockouts, auto-drafts reorders to distributors | n8n webhook + Cognee inventory nodes |
| **Festival Demand** | Seasonal memory from Cognee predicts demand changes before Navratri, Diwali, etc. | Cognee seasonal knowledge graph |

### Architecture
```
Paytm AI Soundbox (UPI/NFC/QR) ──> Sarvam Saaras v4 (STT/TTS)
                                         │
                                    Qora Engine
                                    ├── Bill Audit
                                    ├── Cashflow Predictor
                                    ├── Khata Manager
                                    └── Restock Engine
                                         │
                              ┌──────────┼──────────┐
                              ▼          ▼          ▼
                           Cognee     n8n          Paytm
                         (Memory)  (Automation)  (Lending)
                         847 nodes  7 workflows  Sachet Loans
```

### Tech Stack
- **Voice:** Sarvam Saaras v4 (STT) + Mayura (Translation) + TTS — WebSocket streaming, 22+ languages
- **Memory:** Cognee Extract-Cognify-Load pipeline — LanceDB vector store, persistent knowledge graph
- **Automation:** n8n — WhatsApp Business API triggers, cron workflows, webhook chains
- **Payments:** Paytm AI Soundbox API — UPI, NFC Tap, Dynamic QR, Card

## Run Locally
Open `index.html` in any browser. No dependencies required.