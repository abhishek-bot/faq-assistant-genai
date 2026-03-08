# FAQ Assistant (GenAI)
A FastAPI-based FAQ assistant with fuzzy matching, fallback logic, unanswered query logging, and a simple front-end chatbot UI.  
This project demonstrates how to build a robust, transparent, and demo-ready conversational assistant.

## Overview
This chatbot answers frequently asked questions using a SQLite knowledge base.  
It uses **fuzzy matching** to handle varied phrasing, **fallback logic** to avoid hallucinations, and **logging** to track unanswered queries for continuous improvement.  
A lightweight front-end provides a chat-style interface for interactive demos.
 
This is Weekend 1 of my GenAI hackathon-style learning series.

## Tech Stack
- **Backend**: FastAPI (Python)
- **Database**: SQLite
- **Matching**: RapidFuzz (fuzzy string matching)
- **Frontend**: HTML + JavaScript (served via FastAPI static files)
- **Logging**: Python `logging` module
- **Deployment**: Uvicorn (ASGI server)


## Setup
```bash
git clone https://github.com/abhishek-bot/faq-assistant-genai.git
cd faq-assistant-genai
python -m venv venv
.\venv\Scripts\activate   # Windows
pip install -r requirements.txt
uvicorn app.main:app --reload
