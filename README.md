# rag_using_langchain
A Streamlit-based RAG application that allows users to paste links or YouTube videos and ask questions, retrieving accurate answers using LangChain, OpenAI, FAISS, and HuggingFace embeddings.

# 🔗 RAG Q&A with Streamlit

This project is a **Retrieval-Augmented Generation (RAG) application** built with **Streamlit**.  
It allows users to paste a website link or a YouTube video, ask questions, and get accurate AI-powered answers with supporting sources.  

---

## ✨ Features
- 📥 **Link & YouTube support** – paste any article or video link.  
- 🔎 **Smart text splitting** with `RecursiveCharacterTextSplitter`.  
- 🧠 **Vector search** powered by **FAISS**.  
- 🤖 **LLM integration** with OpenAI (`ChatOpenAI`).  
- 📝 **Embeddings** using HuggingFace models.  
- 🎨 **Clean Streamlit UI** for seamless user experience.  
- 🔐 Secure API handling with `.env`.  

---

## 🚀 Tech Stack
- **Streamlit** – for interactive UI  
- **LangChain** – for RAG orchestration  
- **LangChain-Community** – loaders, vectorstores, embeddings  
- **LangChain-OpenAI** – to connect with OpenAI models  
- **FAISS** – fast vector similarity search  
- **Sentence-Transformers** – HuggingFace embeddings  
- **YouTube Transcript API** – fetch video transcripts  
- **Python-Dotenv** – manage API keys securely  

---

## 📂 Project Structure
📦 Rag_using_langchain
┣ 📜 app.py # Streamlit app
┣ 📜 requirements.txt # Dependencies
┣ 📜 .env.example # API key template
┣ 📜 2rag_using_langchain.ipynb # Notebook (exploration)
┗ 📜 README.md

yaml
Copy code

---

## ⚙️ Installation & Setup

1. **Clone repo**
   ```bash
   git clone https://github.com/<your-username>/rag-using-langchain.git
   cd rag-using-langchain
Create environment

bash
Copy code
conda create -n rag python=3.11 -y
conda activate rag
Install dependencies

bash
Copy code
pip install -r requirements.txt
Set up .env file

env
Copy code
OPENAI_API_KEY=your_api_key_here
Run Streamlit app

bash
Copy code
streamlit run app.py

🎮 Usage
Open the app in browser at http://localhost:8501.

Paste a link (website or YouTube video).

Ask any question related to the content.

Get accurate answers + sources.


🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss.
