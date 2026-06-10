
# 🤖 Sulaiman Faris — AI Personal Assistant

An AI-powered personal assistant that represents me on the web. Built with Python, OpenAI, and Gradio — visitors can ask about my background, skills, projects, and availability, and I get notified instantly.

🔗 **Live Demo:** [huggingface.co/spaces/faris11z/portfolio_assistant](https://huggingface.co/spaces/faris11z/portfolio_assistant)

---

## 💡 What It Does

- Answers questions about my education, skills, projects, and work experience
- Collects contact details from interested visitors and notifies me instantly
- Logs questions it couldn't answer so I can keep improving it
- Powered by GPT-4o-mini with OpenAI function calling (tools)

---

## 🛠️ Tech Stack

- **Python** — core language
- **OpenAI API** — GPT-4o-mini with function calling
- **Gradio** — chat UI
- **ntfy.sh** — instant push notifications
- **pypdf** — LinkedIn PDF parsing

---

## 🚀 Run Locally

1. Clone the repo:
```bash
git clone https://github.com/faris11z/portfolio_assistant.git
cd portfolio_assistant
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Create a `.env` file:
```
OPENAI_API_KEY=your_openai_key
TELEGRAM_BOT_TOKEN=your_token (optional)
TELEGRAM_CHAT_ID=your_chat_id (optional)
```

4. Run:
```bash
python app.py
```

---

## 📁 Project Structure

```
portfolio_assistant/
├── app.py              # Main application
├── requirements.txt    # Dependencies
├── me/
│   ├── summary.txt     # Personal & professional summary
│   └── myprofile.pdf   # LinkedIn profile PDF
└── .env                # API keys (not committed)
```

---

## 👤 About Me

I'm a Master's student in Computer Science at the University of Rostock, Germany, with a focus on AI, Machine Learning, and Data Science.
📧 sulaiman11faris@gmail.com
