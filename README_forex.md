# AI-Powered Forex Trade Journal Analysis System
### Event-driven automation workflow for trader psychology, risk analysis and performance feedback

![n8n](https://img.shields.io/badge/Automation-n8n-FF6D5A?style=flat-square)
![Gemini AI](https://img.shields.io/badge/AI-Gemini-4285F4?style=flat-square)
![Google Sheets](https://img.shields.io/badge/Storage-Google%20Sheets-34A853?style=flat-square)
![Telegram](https://img.shields.io/badge/Delivery-Telegram-26A5E4?style=flat-square)
![Capstone Project](https://img.shields.io/badge/Project-AI%20Automation%20Capstone-8B5CF6?style=flat-square)

---

## 📌 The Problem

Many forex traders keep trade journals — but most are little more than spreadsheets recording entry price, exit price and profit or loss. What they rarely capture consistently is the *why* behind each trade: Was the risk sound? Was the decision emotionally driven? Are the same behavioural patterns recurring across hundreds of trades?

Without systematic analysis, a trader can record 500 trades and still not understand why they keep repeating the same mistakes. The data exists but the insight does not — because extracting it manually is too time-consuming and too subjective to do consistently.

---

## 🎯 Objective

Build an **event-driven AI automation workflow** that:
- Receives trade submissions from traders
- Calculates risk metrics automatically
- Performs AI-powered behavioural and decision analysis
- Routes decisions intelligently based on outcomes
- Delivers personalised feedback to the trader immediately via Telegram
- Stores full analytics historically in Google Sheets for long-term pattern recognition and improvement

---

## ⚡ How It Works

```
Trader submits trade via Google Form
              ↓
    n8n webhook triggered instantly
              ↓
    Risk metrics calculated:
    — R:R ratio
    — Risk percentage of account
    — Position sizing accuracy
    — Stop loss / take profit quality
              ↓
    Gemini AI analyses the trade:
    — Decision quality rating
    — Emotional discipline assessment
    — Risk management evaluation
    — Behavioural pattern flags
              ↓
    Intelligent routing:
    — Good trade → positive reinforcement feedback
    — Poor risk management → specific corrective guidance
    — Emotional trade detected → psychology coaching prompt
              ↓
    Personalised feedback sent via Telegram (immediate)
              ↓
    Full trade analytics stored in Google Sheets
    for historical review and pattern tracking
```

---

## 🛠️ Tools & Technologies

| Component | Tool |
|---|---|
| Workflow Automation | n8n (self-hosted) |
| Trade Submission | Google Forms |
| Risk Calculation | n8n Code nodes (JavaScript) |
| AI Analysis | Google Gemini AI |
| Trader Feedback | Telegram Bot |
| Analytics Storage | Google Sheets |

---

## 📊 What Gets Analysed

### Risk Metrics (calculated automatically)
- **Risk-to-Reward ratio** — actual vs planned
- **Risk percentage** — position size relative to account balance
- **Stop loss placement** — technical validity assessment
- **Position sizing accuracy** — adherence to risk management rules

### AI Behavioural Analysis (Gemini)
- **Decision quality** — was entry/exit based on sound reasoning?
- **Emotional discipline** — signs of fear, greed or revenge trading
- **Risk management rating** — overall trade risk score
- **Pattern detection** — recurring mistakes flagged across trade history

---

## 📁 Repository Contents

```
forex-trade-journal/
├── forex-trade-journal-workflow.json   # n8n workflow — import directly
└── README.md
```

### How to import the workflow
1. Open your n8n instance
2. Click **Workflows → Import from file**
3. Select `forex-trade-journal-workflow.json`
4. Configure your credentials:
   - Google Sheets OAuth
   - Telegram Bot token
   - Gemini API key
5. Activate the workflow

---

## 💡 Key Insight

Consistency in trading is not just about strategy — it is about behaviour. And behaviour only improves when it is measured objectively and consistently. This system makes that measurement automatic, removing the friction between trade execution and actionable insight.

---

## 🔮 Potential Extensions

- [ ] Weekly performance summary report via Telegram
- [ ] Trade streak tracking — winning and losing runs
- [ ] Multi-account support
- [ ] Web dashboard for visual analytics
- [ ] Integration with MetaTrader for automatic trade capture

---

## 👤 Author

**[Your Full Name]**
AI Automation Engineer | NSQ Quality Assurance Assessor
Ogun State, Nigeria

This project was developed as a capstone submission for AI Automation Engineering certification. It demonstrates event-driven workflow design, AI integration, intelligent routing and multi-platform delivery.

- 🔗 LinkedIn: [Your LinkedIn URL]
- 📂 Also see: [QAA AI Assessor Tool](https://github.com/[YOUR_USERNAME]/qaa-assessor-tool) — AI automation applied to vocational education assessment

---

*Built to prove that the gap between data and insight should not exist — automation closes it.*
