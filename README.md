# RAG-powered Q&A Application

This project implements a Retrieval-Augmented Generation (RAG) system using Python and React. It processes documents, creates embeddings, and provides a Q&A interface powered by OpenAI and Supabase.

## Prerequisites

- Python 3.8+
- Node.js 16+
- OpenAI API account
- Supabase account

## Environment Setup

1. Create and activate a Python virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

2. Install Python dependencies:
```bash
pip install -r requirements.txt
```

3. Configure environment variables by creating a `.env` file in the project root:
```plaintext
OPENAI_API_KEY=your_openai_api_key
SUPABASE_URL=your_supabase_project_url
SUPABASE_KEY=your_supabase_api_key
```

## Document Processing

1. Parse your documents:
```bash
python3 rag/parser.py
```

2. Generate embeddings:
```bash
python3 rag/embeder.py
```

3. Start the processing server:
```bash
python3 rag/processor.py
```

## Frontend Setup

1. Install React dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm run dev
```

The application should now be running at `http://localhost:3000` (or your configured port).
