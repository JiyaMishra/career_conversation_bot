# Career Conversation Bot 🤖

An AI-powered career chatbot built with Groq LLM and Gradio, deployed on Hugging Face Spaces.

## 🚀 Live Demo
[Click here to try the bot](https://huggingface.co/spaces/JiyaMishra/Project1AgenticAI)

## 💡 Features
- Chat with an AI version of Jiya Mishra
- Answers questions about career, skills and experience
- Records interested users via Pushover notifications
- Built with Groq LLM (Llama 3.3 70B)

## 🛠️ Setup
1. Clone this repo
2. Copy `.env.example` to `.env`
3. Fill in your own API keys
4. Install dependencies:
```bash
pip install -r 1_foundations/requirements.txt
```
5. Run the app:
```bash
python 1_foundations/app.py
```

## 🔑 API Keys Required
- **GROQ_API_KEY** - Get from [console.groq.com](https://console.groq.com)
- **PUSHOVER_TOKEN** - Get from [pushover.net](https://pushover.net)
- **PUSHOVER_USER** - Get from [pushover.net](https://pushover.net)

## 🏗️ Built With
- [Groq](https://groq.com) - LLM API
-//gradio.app) - UI Framework
- [Pushover](https://pushover.net) - Push Notifications
- [Hugging Face Spaces](https://huggingface.co/spaces) - Deployment
