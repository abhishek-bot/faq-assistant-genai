# FAQ Assistant (GenAI)

## Overview
A GenAI-powered FAQ assistant built with FastAPI, Hugging Face models, and SQLite.  
This is Weekend 1 of my GenAI hackathon-style learning series.

## Tech Stack
- FastAPI
- Hugging Face Transformers
- SQLite

## Setup
```bash
git clone https://github.com/<your-username>/faq-assistant-genai.git
cd faq-assistant-genai
pip install -r requirements.txt
uvicorn app.main:app --reload