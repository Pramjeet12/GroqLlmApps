# Groq LLM Applications

A collection of AI-powered applications using Groq's fast inference API with LLaMA 3.3 70B model.

## Projects

### 1. [MultiDoc-GroqQA](./MultiDoc-GroqQA)
Chat with multiple PDF documents using RAG (Retrieval-Augmented Generation).
- Upload multiple PDFs
- Ask questions in natural language
- Get accurate answers from your documents

### 2. [Text2Sql-GroqQA](./Text2Sql-GroqQA)
Convert natural language questions to SQL queries.
- Ask questions in plain English
- AI generates SQL queries automatically
- Fetches data from SQLite database

## Quick Start

1. **Get your Groq API key** from [Groq Console](https://console.groq.com/keys)

2. **Clone this repository**
   ```bash
   git clone https://github.com/Pramjeet12/GroqLlmApps.git
   cd GroqLlmApps
   ```

3. **Set up environment** (in each project folder)
   ```bash
   cp .env.example .env
   # Edit .env and add your GROQ_API_KEY
   ```

4. **Run a project** - see individual project READMEs for details

## Tech Stack

- **LLM:** LLaMA 3.3 70B (via Groq API)
- **Frontend:** Streamlit
- **Embeddings:** HuggingFace (all-MiniLM-L6-v2)
- **Vector Store:** FAISS
- **Database:** SQLite

## License

MIT
