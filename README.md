📚 AI Research Paper Intelligence System

An AI-powered research assistant that enables semantic search, summarization, keyword extraction, and comparison of machine learning research papers using LLMs and vector search.

🚀 Features

- 🔍 Semantic search with Sentence Transformers
- 📄 AI-generated paper summaries
- 🧠 Keyword extraction using KeyBERT
- ⚖️ Research paper comparison
- 💬 Natural language querying
- ⚡ Fast retrieval with FAISS
- 🤖 LLM integration through LangChain and Groq (Llama 3.1 8B Instant)

🛠 Tech Stack

Category             Technology

Language               Python

Framework             LangChain

LLM              Groq (Llama 3.1 8B Instant)

Embeddings         all-MiniLM-L6-v2

Vector Store           FAISS

NLP               Sentence Transformers

Keyword Extraction     KeyBERT

Environment         Jupyter Notebook

📂 Project Structure

AI-Research-Paper-Intelligence-System/

│── Coding_Blocks_Research_Paper_Intelligence_System.ipynb

│── paper_faiss.index

│── requirements.txt

│── README.md

⚙️ Workflow

User Query
    │
    ▼
Sentence Embeddings
    │
    ▼
FAISS Semantic Search
    │
    ▼
Relevant Papers
    │
    ▼
LLM Processing
    ├── Summary
    ├── Keywords
    └── Comparison
    │
    ▼
Final Response

📦 Installation

git clone https://github.com/yourusername/AI-Research-Paper-Intelligence-System.git
cd AI-Research-Paper-Intelligence-System
pip install -r requirements.txt

▶️ Usage

1. Open the notebook:
   jupyter notebook
2. Run all cells.
3. Enter a research query (e.g., "Deep Learning for Medical Imaging").

The system retrieves relevant papers, generates summaries, extracts keywords, and compares related research.

🎯 Future Enhancements

- Streamlit Web App
- PDF Upload & Chat
- Citation Generation
- RAG-based Q&A
- Research Report Export (PDF/DOCX)
- Multi-Agent Workflow

📚 Concepts Covered

- Semantic Search
- NLP
- Vector Databases
- LLMs
- LangChain
- RAG
- AI Agents

