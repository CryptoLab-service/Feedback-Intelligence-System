# 🧠 Feedback Intelligence System

The **Feedback Intelligence System** is an AI-powered solution designed to automatically collect, analyze, and report on customer and citizen feedback. It empowers organizations such as government agencies like **SERVICOM**, private companies, and service providers to monitor service quality, identify recurring issues, and take proactive action based on real-time insights.

Built on **n8n** and integrated with **Google Sheets**, **Google Gemini**, **Open Source AI** and messaging platforms like **Telegram**, **Slack**, **Discord** and **Whatsapp** this system transforms raw feedback into structured intelligence.

---

## 🚀 Key Features

- ✅ Real-time feedback analysis using LLMs
- 📊 Daily and weekly summary reports
- 🔔 Instant alerts for negative feedback
- 🧠 AI-generated insights and suggestions
- 📁 Google Sheets integration for data logging
- 💬 Multi-platform notifications (Telegram, Slack, Discord, WhatsApp)
- 📱 SMS alerts via Termii or Twilio
- 🔗 OpenRouter support for multi-model LLM routing

---

## 🧩 Core Workflows

### 1. ⚡ Immediate Feedback Analysis and Alert

Triggered whenever a new feedback entry is submitted via Google Sheets.

- Uses **Google Gemini** to analyze feedback
- Extracts:
  - Summary
  - Sentiment (positive, neutral, negative)
  - Pain points
  - Suggestions
- Logs structured output in the **Feedback Summary** sheet
- Sends alerts to relevant teams if sentiment is negative via:
  - Telegram
  - Slack
  - Discord
  - Whatsapp
  - SMS

### 2. 📅 Daily Summary Report

Runs automatically at the end of each day.

- Pulls all feedback submitted that day
- Uses LLM to generate:
  - Total feedback count
  - Recurring themes
  - Highlights of positive feedback
- Sends a formatted summary to a designated **Discord channel** for team leads

### 3. 📈 Weekly & Monthly Comprehensive Analysis

Triggered weekly and monthly.

- Weekly: Generates a report with:
  - Sentiment trends
  - Key themes
  - Actionable recommendations
  - Tabular breakdown of feedback
- Monthly: Adds deeper analysis including:
  - Measures taken by agencies or providers
  - Impact of those measures
  - Suggestions to prevent future negative experiences

---

## 🛠 Technologies Used

- [n8n](https://n8n.io/) – Workflow automation
- [Google Sheets](https://www.google.com/sheets/about/) – Data collection and logging
- [Google Gemini](https://gemini.google.com/) – LLM for feedback analysis
- [DeepSeek](https://chat.deepseek.com/) – LLM for feedback analysis
- [OpenRouter](https://openrouter.ai/) – Multi-model LLM routing and experimentation
- [Telegram](https://core.telegram.org/bots) – Alert delivery
- [Slack](https://api.slack.com/) – Team notifications
- [Discord](https://discord.com/developers/docs/intro) – Summary reporting
- [WhatsApp Business](https://web.whatsapp.com/) – Feedback collection and alert delivery
- 📱 SMS Gateway (Twilio or Termii) – Mobile alerts and citizen engagement

---

## 🔮 Future Enhancements

- 🧠 **Advanced Sentiment and Topic Analysis**  
  Move beyond basic sentiment categories by introducing a scale (e.g., -5 to +5) and dynamic topic modeling to uncover hidden issues.

- ✅ **Automated Action Item Creation**  
  Automatically create tasks in Trello, Jira, or Notion for highly negative feedback, ensuring complaints are tracked and resolved.

- 🔗 **CRM and Support System Integration**  
  Link feedback to customer profiles in CRM platforms for a complete view of user interactions and history.

- 🌐 **Multi-Channel Data Ingestion**  
  Expand beyond Google Sheets to ingest feedback from emails, social media, web forms, and voice transcripts.

- 📊 **Predictive Analytics**  
  Forecast service bottlenecks or emerging issues using historical feedback trends.

- 📈 **Interactive Dashboard**  
  Visualize feedback data in tools like Google Data Studio or Power BI for deeper analysis and filtering.

- 🔁 **Feedback Loop Closure**  
  Automatically follow up with users after issue resolution to confirm satisfaction and gather additional insights.

---

## 📂 Repository Structure

/workflows ├── immediate-feedback.n8n.json ├── daily-summary.n8n.json └── weekly-analysis.n8n.json

/docs └── report-samples/ ├── daily-summary.md └── weekly-analysis.md

---

## 📬 Contact & Contribution

Built by **TOLUWALOPE JOHN OLUWALOWO**  
GitHub: [CryptoLab-service](https://github.com/CryptoLab-service/)  
Email: oluwalowojohn@gmail.com

Whatsapp: [07030739128](https://whatsapp.me/+2347030739128/)
Location: Nigeria 🇳🇬

> This project is actively maintained and open to contributions. Feel free to fork, improve, or collaborate.

---

> Empowering smarter service delivery through intelligent feedback.
