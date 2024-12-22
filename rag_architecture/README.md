RAG Architecture

 

✨ Objective

This project demonstrates a RAG (Retrieval-Augmented Generation) architecture combining information retrieval and natural language generation to enhance AI responses.

🛠️ Technologies Used

Language and Frameworks: Python

Libraries:

Transformers

Sentence-Transformers

FAISS

Pre-trained Models: T5-small and all-MiniLM-L6-v2

📜 Installation

Clone the repository:

git clone https://github.com/yourusername/rag-architecture.git

Navigate to the directory:

cd rag-architecture

Install dependencies:

pip install transformers sentence-transformers faiss-cpu

📂 Project Structure

📦 rag-architecture
├── 📄 main.py
├── 📄 README.md
├── 📄 requirements.txt
└── 📂 data

📊 Workflow

Document Indexing: Generate embeddings for documents.

Document Retrieval: Search for relevant documents using FAISS.

Answer Generation: Generate responses using the T5 model based on retrieved documents.

📖 Example Usage

Run

python main.py

Expected Output

Question: What is Bitcoin?
Answer: digital currency
