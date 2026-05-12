# 🚀 PrivateGPT – Secure Offline AI Assistant

![PrivateGPT Banner](https://raw.githubusercontent.com/zylon-ai/private-gpt/main/fern/docs/assets/ui.png)

## 📌 Overview

**PrivateGPT** is a production-ready private AI framework that enables you to interact with your documents using Large Language Models (LLMs) completely offline and securely.

Built with privacy-first architecture, PrivateGPT ensures that **no data leaves your local environment**, making it ideal for sensitive industries such as healthcare, finance, defense, legal, and enterprise systems.

---

## ✨ Features

* 🔒 100% Private & Offline AI
* 📄 Chat with PDFs, Docs & Text Files
* ⚡ FastAPI-based OpenAI-compatible APIs
* 🧠 Retrieval-Augmented Generation (RAG)
* 📚 Document Ingestion & Semantic Search
* 🌐 Streaming & Normal Chat Responses
* 🖥️ Built-in Gradio UI
* 🔧 Modular & Extendable Architecture
* 🧩 Supports Custom Embedding & LLM Models

---

## 🏗️ Tech Stack

| Technology          | Usage               |
| ------------------- | ------------------- |
| Python              | Backend Development |
| FastAPI             | API Framework       |
| LlamaIndex          | RAG Pipeline        |
| Qdrant              | Vector Database     |
| Gradio              | Web Interface       |
| OpenAI API Standard | API Compatibility   |

---

## 📂 Project Architecture

```bash id="y5bsf6"
private_gpt/
│
├── server/                 # API routes & services
├── components/             # LLM & embedding components
├── ingestion/              # Document ingestion pipeline
├── ui/                     # Gradio UI
├── models/                 # Local model configurations
├── tests/                  # Unit & integration tests
└── configs/                # Application configuration
```

---

## ⚙️ Installation

### 1️⃣ Clone Repository

```bash id="4htsj5"
git clone https://github.com/your-username/privategpt.git
cd privategpt
```

### 2️⃣ Create Virtual Environment

```bash id="b0q5ph"
python -m venv venv
```

### 3️⃣ Activate Environment

#### Windows

```bash id="hho6rm"
venv\Scripts\activate
```

#### Linux / macOS

```bash id="r10v1k"
source venv/bin/activate
```

### 4️⃣ Install Dependencies

```bash id="ryqz7l"
pip install -r requirements.txt
```

---

## ▶️ Running the Application

### Start Backend Server

```bash id="jqmhhc"
python -m private_gpt
```

### Launch Gradio UI

```bash id="8nlvgi"
python scripts/setup
```

---

## 📄 Document Ingestion

Add your documents inside the `documents/` folder and run:

```bash id="5pxv5k"
python scripts/ingest.py
```

Supported formats include:

* PDF
* TXT
* DOCX
* CSV
* Markdown

---

## 🔍 API Capabilities

### High-Level APIs

* Document ingestion
* Context-aware chat
* Semantic retrieval
* Prompt orchestration

### Low-Level APIs

* Embedding generation
* Vector search
* Custom RAG pipelines

---

## 📸 UI Preview

![UI Screenshot](https://raw.githubusercontent.com/zylon-ai/private-gpt/main/fern/docs/assets/ui.png)

---

## 💡 Use Cases

* Enterprise Knowledge Assistant
* Offline AI Chatbot
* Research Assistant
* Legal/Medical Document QA
* Secure Internal AI Tools
* AI-powered Search Engine

---

## 🧠 Why PrivateGPT?

Traditional AI applications rely heavily on cloud infrastructure, which introduces security and compliance concerns.

PrivateGPT solves this by:

* Running locally
* Keeping data private
* Supporting offline deployments
* Providing enterprise-grade architecture

---

## 🤝 Contributing

Contributions are welcome!

### Run Quality Checks

```bash id="ct36f8"
make check
```

### Run Tests

```bash id="fgho43"
make test
```

## 📜 License

This project is licensed under the **Apache 2.0 License**.

---

## 👨‍💻 Author

Developed by **Sujal Deshmukh** and the open-source community.

---

## ⭐ If you like this project

Give it a ⭐ on GitHub and contribute to the community!

---


