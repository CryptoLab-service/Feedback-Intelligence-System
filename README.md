# 🧠 Feedback Intelligence System

The **Feedback Intelligence System** is an AI-powered solution designed to automatically collect, analyze, and report on customer and citizen feedback. It empowers organizations—such as government agencies like **SERVICOM**, private companies, and service providers—to monitor service quality, identify recurring issues, and take proactive action based on real-time insights.

Built on **n8n** and integrated with **Google Sheets**, **Google Gemini**, and messaging platforms like **Telegram**, **Slack**, and **Discord**, this system transforms raw feedback into structured intelligence.

---

## 🚀 Key Features

- ✅ Real-time feedback analysis using LLMs
- 📊 Daily and weekly summary reports
- 🔔 Instant alerts for negative feedback
- 🧠 AI-generated insights and suggestions
- 📁 Google Sheets integration for data logging
- 💬 Multi-platform notifications (Telegram, Slack, Discord)

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
- [Telegram](https://core.telegram.org/bots) – Alert delivery
- [Slack](https://api.slack.com/) – Team notifications
- [Discord](https://discord.com/developers/docs/intro) – Summary reporting

---

## 💡 Future Enhancements

- 🔍 Add keyword-based filtering for urgent issues (e.g. “fraud”, “delay”, “harassment”)
- 📍 Geo-tagging feedback to identify regional service gaps
- 📊 Dashboard integration for real-time visualization
- 🧾 PDF export of weekly/monthly reports
- 🧠 Sentiment trend prediction using time-series modeling
- 🗣️ Multilingual feedback support with translation layer

---

## 📂 Repository Structure

