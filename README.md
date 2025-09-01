# RssAiNewsClassifier

![Workflow](https://raw.githubusercontent.com/TuguiDragos/RssAiNewsClassifier/refs/heads/main/workflow.png)

## Overview
**RssAiNewsClassifier** is an automation workflow built with [n8n](https://n8n.io) that fetches the latest news from any **RSS feed**, processes articles with **DeepSeek LLM**, and delivers only the most relevant alerts directly to your **Slack** workspace.

It’s designed to cut through the noise:  
- ✅ Summarizes articles in plain English  
- ✅ Detects sentiment (positive / negative / neutral)  
- ✅ Tags important events with flags (`funding`, `acquisition`, `product_launch`, `hiring`)  
- ✅ Sends real-time alerts to Slack  

![Slack Preview](https://raw.githubusercontent.com/TuguiDragos/RssAiNewsClassifier/refs/heads/main/Message.png)

## Why use it?
If you’re tracking **AI, startups, finance, or tech industry news**, this workflow saves hours of manual reading. Instead of scanning dozens of feeds, you get clean summaries and alerts for only what matters.  

Perfect for:  
- 🚀 Startup founders tracking competition & funding  
- 📈 Investors monitoring acquisitions and product launches  
- 🤖 Tech enthusiasts following AI and robotics news  
- 📰 Teams who want real-time Slack alerts without noise  

## Requirements
- A **Slack bot token** (create via [Slack API](https://api.slack.com/apps))  
- A **DeepSeek API key**  

## Setup
1. Clone this repo  
2. Import the workflow into **n8n**  
3. Add your Slack bot token & DeepSeek API key  
4. Deploy → start getting smart news alerts  

## Links
🌍 More projects: [tuguidragos.com](https://tuguidragos.com)  
☕ Support my work: [buymeacoffee.com/tuguidragos](https://buymeacoffee.com/tuguidragos)  

---

🚨 Stop wasting time on irrelevant news ! Let AI classify, summarize, and deliver what really matters, straight to your Slack.
