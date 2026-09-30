# 🌉 ManakSetu (मानक सेतु) — BIS AI Assistant
### **Smart India Hackathon 2026 | Problem Statement 26107**
**Ministry of Consumer Affairs, Food & Public Distribution / Bureau of Indian Standards (BIS)**

---

## 📌 Executive Summary
**ManakSetu** is an AI-powered intelligent assistant and conformity assessment platform designed to bridge the gap between dense technical Indian Standards (IS codes, QCO mandates, hallmarking rules) and everyday industries, MSMEs, and consumers. It translates complex regulatory compliance into an intuitive, real-time discovery and verification journey.

---

## ✨ Core Features & Modules

1. **Smart Standard Finder (For Manufacturers & MSMEs):**
   - Instant search across Indian Standards (IS codes, titles, and scopes).
   - Category filtering (Food & Water, Electrical, Jewellery, Consumer Goods, Civil & Steel).
   - Interactive modal drawers detailing mandatory Quality Control Orders (QCO) and mandatory NABL/BIS lab test parameters.
2. **Consumer Trust & Authenticator Hub:**
   - Instant validation of 6-digit Hallmark Unique Identification (HUID) for gold jewellery and ISI CM/L license numbers against official mock central registries.
   - Built-in counterfeit/fraud alert triggers and simulated camera QR/hallmark scanning.
3. **Interactive Fee Estimator & Roadmap:**
   - Dynamic quotation calculator incorporating official statutory concessions (50% fee rebate for Micro units and women entrepreneurs, 20% for Small units).
   - Visual 5-step Scheme-I licensing lifecycle roadmap (Manakonline application $\rightarrow$ in-house QC $\rightarrow$ lab testing $\rightarrow$ factory audit $\rightarrow$ grant of license).
4. **Bilingual AI Assistant (English & हिंदी):**
   - Interactive conversational consultation with instant responses to QCO regulations, testing norms, and fee queries.
   - Built-in bilingual speech synthesis (`🔊 Listen (EN)` and `🔊 सुनें (HI)`) simulating Bhashini regional accessibility.

---

## 🛠️ Technology Stack

* **Frontend & UI:** HTML5, Tailwind CSS (via CDN for zero-configuration lightning speed), and Google Fonts (*Plus Jakarta Sans*).
* **Icons:** Lucide Icons.
* **Localization & Voice:** Vanilla JavaScript state management with browser-native Web Speech API (`SpeechSynthesis`) supporting English (`en-IN`) and Hindi (`hi-IN`).
* **Deployment Architecture:** Zero-installation single-file web application (`index.html`), fully compatible with offline hackathon judging environments.

---

## 🚀 How to Run Locally

1. Download or copy the project code into a file named **`index.html`**.
2. Double-click **`index.html`** or open it in any modern web browser (Google Chrome, Microsoft Edge, Safari). No terminal commands or Node.js installations required!

---

## 🔮 Future Upgrades & Production Roadmap

To scale **ManakSetu** from a hackathon prototype into a national-level enterprise deployment for the Bureau of Indian Standards, the following upgrades are planned:

### 1. Native Bhashini Neural API Integration
* **Current State:** Uses browser speech synthesis for English and Hindi.
* **Future Upgrade:** Integrate official **AI4Bharat / Bhashini APIs** for real-time speech-to-text (STT) and text-to-speech (TTS) across all 22 scheduled Indian languages, empowering rural artisans and small shopkeepers to query standards using vernacular voice notes.

### 2. OCR Spec-Sheet & Packaging Analyzer (Multimodal AI)
* **Current State:** Text keyword search and manual dropdown filters.
* **Future Upgrade:** Implement a Vision-Language Model (VLM) pipeline. Manufacturers can upload product packaging images, material composition bills of materials (BOM), or lab spec sheets. The AI will automatically parse parameters and output the precise applicable IS code and QCO mandate.

### 3. Blockchain-Backed HUID Traceability Ledger
* **Current State:** Centralized mock registry validation.
* **Future Upgrade:** Anchor gold hallmarking HUID data and ISI license lifecycles onto a permissioned government blockchain ledger. This ensures immutable tracking from assaying centers to retail storefronts, making tampering or duplicate HUID stamping cryptographically impossible.

### 4. Automated IoT & Telemetry Factory Audits
* **Current State:** Static 5-step licensing roadmap.
* **Future Upgrade:** Direct API integration with the BIS *Manakonline* portal. Enable automated IoT sensor verification for in-house quality control testing equipment and streamline digital appointment scheduling for BIS technical officers conducting factory audits.

### 5. Offline-First Mobile Application (Flutter / PWA)
* **Current State:** Responsive web application.
* **Future Upgrade:** Package ManakSetu into a Progressive Web App (PWA) and native mobile app (Flutter) with offline caching of high-frequency IS codes, enabling field inspectors and consumers in remote areas to scan QR/HUID codes even with intermittent network connectivity.
