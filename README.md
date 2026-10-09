# TrustWork 🛡️ — AI Job Fraud Detection & Career Safety Platform

TrustWork is an AI-powered job fraud detection and career safety web platform designed to protect job seekers from employment scams, fake recruitment drives, and phishing offers. It combines client-side heuristic threat detection, real-time risk signal analysis, and deep LLM auditing powered by the Google Gemini API.

Live Demo: [https://hrishitachoudhury2006-glitch.github.io/Trustwork/](https://hrishitachoudhury2006-glitch.github.io/Trustwork/)

---

## ✨ Features

### 🔍 1. AI Job Fraud Detection & Threat Scoring
- **Interactive Risk Gauge:** Visualizes threat levels from 0 to 100 with actionable risk statuses (Safe, Low Risk, Moderate Suspicion, High Risk Scam).
- **Multi-Dimensional AI Threat Radar:** Canvas-rendered radar chart evaluating risk across 5 critical vectors:
  - Financial Red Flags (registration fees, upfront payments, equipment charges)
  - Urgency & Pressure Tactics ("immediate joining", "limited slots")
  - Contact Authenticity (WhatsApp/Telegram vs official enterprise domains)
  - Job Requirements & Vagueness (unrealistic salaries, zero experience requirements)
  - Domain & URL Trust Verification
- **Live Risk Ticker:** Instant pattern matching as you type or paste job postings.
- **Built-in Benchmark Samples:** Pre-loaded samples to test both verified corporate jobs (e.g., TCS, Infosys) and common recruitment scams (WFH data entry scams, modern impersonation frauds).

### 🤖 2. Google Gemini AI Deep Audit
- Connect your own Google Gemini API key securely in the UI.
- The key is saved strictly in browser `localStorage` and never sent to any intermediary server.
- Performs contextual natural language analysis, identifying hidden manipulation patterns, fake recruiter personas, and inconsistent compensation promises.

### 📄 3. AI Resume & ATS Quality Optimizer
- **ATS Compatibility Score:** Analyzes resume structure, quantifiable achievements, and action verb strength.
- **Missing & Strong Keyword Analysis:** Identifies critical keywords missing for target job roles.
- **AI Rewriting Engine:** Generates ATS-optimized summaries, enhanced bullet points, and actionable tips to boost interview callback rates.

### 🔒 4. Privacy & Performance
- **Zero Backend Required:** 100% client-side application running directly in the browser.
- **Lightweight & Fast:** Built with vanilla web standards, SVGs, and native Canvas without heavy framework overhead.

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3 (Modern Design System with CSS Custom Properties), Vanilla JavaScript (ES6+)
- **Visualizations:** HTML5 Canvas API (Dynamic Gauge Meter & 5-Axis Threat Radar)
- **AI Engine:** Google Gemini API
- **Typography:** Outfit & JetBrains Mono (via Google Fonts)
- **Hosting:** GitHub Pages

---

## 🚀 Getting Started

### Option 1: Run Locally
1. Clone this repository:
   ```bash
   git clone https://github.com/hrishitachoudhury2006-glitch/Trustwork.git
   cd Trustwork
   ```
2. Open `index.html` in any modern web browser:
   - On Windows: Double-click `index.html` or run:
     ```powershell
     Start-Process index.html
     ```
   - Using VS Code Live Server: Right-click `index.html` and click **Open with Live Server**.

### Option 2: Live GitHub Pages
Visit: [https://hrishitachoudhury2006-glitch.github.io/Trustwork/](https://hrishitachoudhury2006-glitch.github.io/Trustwork/)

---

## 🔑 Gemini AI Setup (Optional)

1. Get a free API key from [Google AI Studio](https://aistudio.google.com/).
2. Open TrustWork in your browser.
3. Paste your API key into the top banner (`Connect Gemini AI`) and click **Connect**.
4. The key will be stored securely in your browser's local storage for your sessions.

---

## 📂 Repository Structure

```text
├── index.html        # Main application entry point (single-page app)
└── README.md         # Project documentation and setup guide
```

---

## 🛡️ License

This project is open-source and available under the [MIT License](LICENSE).
