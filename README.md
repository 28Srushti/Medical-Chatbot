# 🩺🤖 Medical Chatbot
    A retrieval-augmented medical Q&A chatbot that indexes your medical PDFs and answers questions grounded in those documents—focused, factual, and fast.

## ✨ Features
    🔎 Document-grounded answers: Queries are answered strictly from your PDF corpus.
    🧠 Domain embeddings: PubMedBERT embeddings for medical text recall.
    💬 Chat loop: Ask follow-ups and refine questions interactively.
    🧱 Chroma vector store: Fast, lightweight retrieval.
    ⚡ Local LLM (llama.cpp): Private and efficient inference.
    🎯 Concise prompting: Truthful, direct responses by design.

## 🧰 Tech Stack
    🧠 Embeddings: NeuML/pubmedbert-base-embeddings (Sentence Transformers)
    🧾 Vector DB: Chroma
    🤖 LLM: LlamaCpp (llama.cpp)
    🧱 Load/Split: PyPDFDirectoryLoader, RecursiveCharacterTextSplitter
    🧩 Orchestration: LangChain Runnable + ChatPromptTemplate

## 🚀 How to Clone & Run
    git clone https://github.com/xyz/Medical-Chatbot.git
    cd Medical-Chatbot

    


