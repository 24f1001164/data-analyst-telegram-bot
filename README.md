# data-analyst-telegram-bot

data-analyst-telegram-bot/
│
├── main.py
├── telegram_bot.py
├── agent.py
├── logger.py
├── test_ai.py
├── requirements.txt
├── .env   (in this add your api tokens)
└── README.md   

# Data Analyst Telegram Bot

LLM-powered Telegram bot that answers data analysis questions and returns JSON responses.

## Features

- Telegram Bot API integration
- LLM agent using Groq API
- JSON-only responses
- Data analysis reasoning
- JSONL logging

## Setup
Install dependencies:
pip install -r requirements.txt


## Architecture
Telegram User
↓
Telegram Bot
↓
AI Agent
↓
Groq LLM
↓
JSON Response
