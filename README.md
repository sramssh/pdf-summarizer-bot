# pdf-summarizer-bot
A Retrieval-Augmented Generation (RAG) AI bot that summarizes PDF chapters using vector embeddings and GPT models.

## Features
- Extracts text from PDFs
- Splits content into manageable chunks
- Stores embeddings in ChromaDB
- Queries relevant chunks and summarizes with GPT
- Easily extensible to any PDF or LLM

## Installation
```bash
git clone <repo-url>
cd pdf-summarizer-bot
pip install -r requirements.txt
cp .env.example .env  # add your API key
