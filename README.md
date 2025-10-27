# N8N-AI-Automation
# 🧠 Telegram AI Daily News Bot (n8n + OpenAI)

This project automates **Daily news delivery on Telegram using n8n, OpenAI, and news APIs**.  
It fetches current headlines, summarizes them using GPT, and sends concise updates via a Telegram bot.

🚀 Features
- 📰 Fetches top news automatically every morning  
- 🧠 Uses OpenAI GPT model for natural summaries  
- 💬 Sends daily updates directly to your Telegram chat  
- 🔁 Fully automated via n8n scheduler

🛠️ Tools & APIs Used
- [n8n](https://n8n.io) (Automation platform)  
- [OpenAI API](https://platform.openai.com)  
- [Telegram Bot API](https://core.telegram.org/bots)  
- [NewsAPI.org](https://newsapi.org/) or any other RSS/Custom news source  

🧩 Workflow Overview
1. Trigger – Send Text 'Hi'
2. HTTP Node – Fetches latest news  
3. OpenAI Node – Summarizes articles in simple terms  
4. Telegram Node – Sends AI-generated news to users  
