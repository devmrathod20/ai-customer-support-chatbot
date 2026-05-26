# AI Customer Support Chatbot using n8n + Gemini AI + Telegram

## Overview

This project is a real-time AI-powered customer support chatbot built using n8n workflow automation, Google Gemini AI, and Telegram Bot API.

The chatbot receives user messages through Telegram, processes them using Gemini AI, and sends intelligent responses instantly.

This project demonstrates:
- AI chatbot automation
- Workflow orchestration
- API integration
- Telegram bot development
- Real-time conversational AI
- Cloud deployment architecture

---

# Features

- AI-powered chatbot using Google Gemini
- Telegram chatbot integration
- Real-time AI responses
- n8n workflow automation
- Dynamic prompt handling
- Professional customer support behavior
- Cloud deployment ready
- GitHub version control ready

---

# Tech Stack

| Technology | Purpose |
|---|---|
| n8n | Workflow Automation |
| Google Gemini AI | AI/LLM Responses |
| Telegram Bot API | Chatbot Platform |
| Railway | Cloud Deployment |
| GitHub | Version Control |
| Webhooks | Real-Time Communication |

---

# Workflow Architecture

```text
Telegram User
      ↓
Telegram Trigger (n8n)
      ↓
Edit Fields
      ↓
Basic LLM Chain
      ↓
Google Gemini Chat Model
      ↓
Format Reply
      ↓
Telegram Send Message
      ↓
Telegram User
