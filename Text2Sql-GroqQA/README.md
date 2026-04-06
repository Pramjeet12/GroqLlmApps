# Text to SQL using Groq API

Convert natural language questions to SQL queries using LLaMA 3.3 70B model.

## Features
- Ask questions in plain English
- AI generates SQL queries automatically
- Fetches data from SQLite database
- Simple Streamlit web interface

## Setup

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Add your Groq API key in `.env`:
```
GROQ_API_KEY=your_key_here
```

3. Initialize database (once):
```bash
python sqlite.py
```

4. Run the app:
```bash
streamlit run app.py
```

## Tech Stack
- Python
- Streamlit
- Groq API (LLaMA 3.3 70B)
- SQLite

## Sample Questions
- "How many students are there?"
- "Show all students in Data Science class"
- "Who has the highest marks?"
