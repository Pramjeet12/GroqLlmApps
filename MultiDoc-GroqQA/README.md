# MultiDoc-GroqQA

Chat with multiple PDF documents using Llama 3.3 70B powered by Groq API.

## Features

- Upload multiple PDF files
- Ask questions in natural language
- Get accurate answers from your documents
- Fast responses using Groq's inference engine

## Tech Stack

- **Frontend:** Streamlit
- **LLM:** Llama 3.3 70B (via Groq API)
- **Embeddings:** HuggingFace (all-MiniLM-L6-v2)
- **Vector Store:** FAISS

## Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/Pramjeet12/GroqLlmApps.git
   cd GroqLlmApps/MultiDoc-GroqQA
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure environment**

   Create a `.env` file:
   ```
   GROQ_API_KEY=your_groq_api_key_here
   ```

   Get your API key from [Groq Console](https://console.groq.com/keys)

4. **Run the app**
   ```bash
   streamlit run app.py
   ```

## Usage

1. Upload PDF files using the sidebar
2. Click "Submit & Process"
3. Ask questions in the text input
4. Get answers based on your documents

## License

MIT
