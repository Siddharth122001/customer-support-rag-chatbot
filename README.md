# Customer Support Chatbot using RAG

This project implements a Retrieval-Augmented Generation (RAG) based
customer support chatbot using open-source LLMs and real-world support data.

## 🚀 Features
- Semantic search using sentence embeddings
- Retrieval-Augmented Generation (RAG)
- Instruction-tuned LLM (FLAN-T5)
- Interactive chatbot UI in Google Colab
- Uses real customer support dataset (Bitext)

## 🛠️ Tech Stack
- Python
- Hugging Face Transformers
- SentenceTransformers
- FLAN-T5
- Google Colab

## 📂 Dataset
Bitext Customer Support LLM Chatbot Training Dataset  
https://huggingface.co/datasets/bitext/Bitext-customer-support-llm-chatbot-training-dataset

## 🧠 How it Works
1. User query is converted into embeddings
2. Most relevant support responses are retrieved
3. Retrieved context is passed to the LLM
4. LLM generates a grounded response

## ▶️ How to Run
1. Open the notebook in Google Colab
2. Run all cells
3. Ask customer support questions in the chat UI

## 📌 Example
**User:** My account is locked  
**Bot:** If your account is locked, please wait and try again or contact support.

## 📄 Author
Siddharth Singh
