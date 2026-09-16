# Qora — Autonomous AI Business Partner for Paytm Merchants

> **Track 1:** Merchant Growth AI — Build the AI business partner for every Paytm merchant  
> **Submission Round:** Official Pitch Deck & Working Demonstration  
> **Tech Stack:** Sarvam AI (Voice Copilot) + n8n (Autonomous Orchestration) + Cognee (E-C-L Memory Graph) + Paytm AI Soundbox & Lending APIs

---

## 🔗 Quick Links
- **Interactive Live Demo:** [https://fursatiinsaan.github.io/Qora/](https://fursatiinsaan.github.io/Qora/)
- **Pitch Deck (PDF):** [Download Qora_Pitch_Deck.pdf](https://github.com/fursatiinsaan/Qora/raw/main/Qora_Pitch_Deck.pdf)
- **Pitch Deck (PPTX):** [Download Qora_Pitch_Deck.pptx](https://github.com/fursatiinsaan/Qora/raw/main/Qora_Pitch_Deck.pptx)

---

## 📌 Executive Summary
India's 30M+ small merchants run daily commerce on mental math, paper khatas, and manual WhatsApp coordination. They lose thousands every month to unnoticed supplier overcharges, chronic credit delays, stockouts, and working capital crunches.

**Qora** converts existing **Paytm Soundbox** infrastructure into a proactive, multilingual AI business partner that manages back-office operations autonomously in the merchant's native language.

---

## 💡 Key Innovations & Capabilities

### 1. Voice-First Multilingual Copilot (Sarvam AI)
- **Native Indic Interaction:** Speaks and listens across 11+ Indian languages (Hindi, Tamil, Telugu, Kannada, Bengali, Marathi, Gujarati, etc.) using Sarvam Saaras v4 STT & TTS.
- **Code-Mixing Support:** Seamlessly parses colloquial queries (e.g. *"Aaj kitna galla aaya?"*, *"Amul waale ko kitna dena hai?"*).
- **Sub-Second Streaming:** Real-time WebSocket streaming with zero app fatigue.

### 2. Autonomous Supplier Bill Audit Engine
- **Automated Ingestion:** Merchants forward supplier invoices or delivery receipts via WhatsApp.
- **Contract Verification:** Extracted line items are cross-checked against contracted rates stored in Cognee memory.
- **Dispute Automation:** Flags overcharges instantly (e.g. rate drift on dairy or staples) and drafts pre-filled dispute notices to distributors.

### 3. Long-Term Merchant Knowledge Graph (Cognee)
- **Extract-Cognify-Load (E-C-L) Pipeline:** Persists semantic relationships across 800+ nodes.
- **Customer Profiles:** Tracks purchase frequency, average basket size, and credit repayment discipline.
- **Seasonal Demand Forecasting:** Anticipates seasonal spikes (e.g. Navratri snack surges vs. dairy dips; Diwali dry fruits).

### 4. Smart Khata & Cashflow Automation (n8n)
- **Credit Collection Workflows:** Auto-triggers polite, localized WhatsApp audio and text reminders when khata accounts exceed grace periods.
- **Sachet Working Capital:** Evaluates real-time Soundbox inflow velocity to pre-qualify merchants for instant micro-credit (₹25K–₹75K) with daily auto-debit settlements.
- **Stockout Prevention:** Automatically calculates burn rates and drafts distributor purchase orders 24 hours prior to stock depletion.

---

## 🏗 System Architecture

```
Paytm AI Soundbox (UPI / NFC / QR)
       │
       ▼
Sarvam Saaras v4 (STT / Indic NLP) ◄──► Sarvam TTS (Voice Response)
       │
       ▼
  Qora Engine (Core Orchestrator)
  ├── Supplier Audit Module
  ├── Khata & Credit Engine
  ├── Cashflow & Velocity Scorer
  └── Restock Predictor
       │
       ├─────────────────────────┬─────────────────────────┐
       ▼                         ▼                         ▼
Cognee Memory Graph          n8n Workflow Engine       Paytm APIs
- Customer Behavior Nodes    - WhatsApp Business API   - Soundbox Ingestion
- Contracted Price Ledger    - Invoice OCR & Audit     - Sachet Lending
- Seasonal Trend Memory      - Daily P&L Broadcast     - Settlement Hook
```

---

## 📊 Presentation Deck Structure (7 Slides)
1. **Title & Vision:** Autonomous AI Business Partner for Every Paytm Merchant
2. **The Problem:** The Hidden Leakages of India's 30M+ Merchants (Overcharges, Khata Defaults, Manual Drag)
3. **The Solution:** The 3-Tier AI Stack (Sarvam AI + Cognee + n8n)
4. **System Architecture & Tech Stack:** Data flow from Soundbox to Memory & Automation
5. **Product Features:** 6 Core Capabilities in One Platform
6. **Impact & Paytm Moat:** Revenue generation, retention, and merchant unit economics
7. **Summary & Verification:** Live Links and Deployment

---

## 🚀 Running Locally
Simply clone the repository and open `index.html` in any browser. No installation or build steps required.