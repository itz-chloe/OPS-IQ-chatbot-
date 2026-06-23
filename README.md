# OPS-IQ-chatbot-
I am currently building ‘OpsIQ’, an AI-powered operations chatbot that allows users to query a real-world supply chain database using simple questions.
# OpsIQ – AI-Powered Operations Chatbot

It will allow users to query a real-world 180,000+ row supply chain 
database using plain English questions — no SQL knowledge required.

## What it does
- Accepts plain English questions about supply chain operations
- Converts them into SQL queries using a large language model API
- Runs the query against a real logistics database
- Returns a plain English answer with optional data visualisations

## Tech Stack
- Python, pandas
- SQLite
- LLM API (Claude by Anthropic)
- Streamlit
- Jupyter Notebook

## Dataset
DataCo Smart Supply Chain dataset — download from Kaggle and place 
the CSV in the data/ folder:
https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis

## Project Status
🚧 Currently in development — Phase 1 (data foundation) complete

## Phases
- ✅ Phase 1 — Data cleaning, preprocessing and database design
- 🔜 Phase 2 — NL-to-SQL pipeline using LLM API
- ⏳ Phase 3 — Streamlit web interface and deployment
- ⏳ Phase 4 — Polish and optimisation
