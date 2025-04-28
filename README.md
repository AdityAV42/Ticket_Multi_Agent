# Ticket_Multi_Agent
# CSV-based RAG Pipeline using Ollama, ChromaDB, and LangChain

This project implements a lightweight Retrieval-Augmented Generation (RAG) pipeline that works with `.csv` files instead of PDFs.  
It uses **Ollama** for embeddings and language model inference, **ChromaDB** as a vector database, and **LangChain** for chaining components together.

---

## 🛠️ Tech Stack

- **Ollama** (LLM and embedding model serving)
- **ChromaDB** (open-source vector database)
- **LangChain** (framework for LLM apps)
- **FastEmbed** (efficient embedding with Ollama)
- **Sentence Transformers** (alternative embeddings)

---

## 📦 Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/your-repo-name.git
    cd your-repo-name
    ```

2. Create a virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Make sure **Ollama** is installed and running locally.  
   Example to pull required models:

    ```bash
    ollama pull nomic-embed-text
    ollama pull llama3
    ```

---

## 📂 Project Structure

```text
├── data/
│   └── Historical_ticket_data.csv    # Your CSV file
├── app.py                             # Main Python code (RAG pipeline)
├── requirements.txt                   # Python dependencies
└── README.md                          # Project description
