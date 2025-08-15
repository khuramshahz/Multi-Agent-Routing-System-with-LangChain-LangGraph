# 🤖 Multi-Agent Routing System with LangChain & LangGraph

<p align="center">
  <img src="./assets/animated_header.svg" alt="Animated Banner" />
</p>

> **Empowering intelligent query routing with AI — built for precision, scalability, and speed!**

---

## 🌟 Project Overview
Welcome to the **Multi-Agent Routing System**, an AI-powered solution that routes user queries to the most relevant data source — a **vector-based internal knowledge base** or **Wikipedia**.  
Built with **LangChain**, **LangGraph**, **Groq LLMs**, and **Astra DB**, it delivers precise, context-aware responses with a modular and scalable design.

### 🔀 Routing Destinations
- 🔍 **Wikipedia** for general knowledge questions.
- 🧠 **Astra DB Vector Store** for domain-specific insights *(AI agents, prompt engineering, LLM attacks)*.

---

## ✨ Key Features

- 🧠 **Smart Query Routing** — Groq's **Gemma-2 9B Instruct** LLM selects the best source.
- 🔄 **State Machine Workflow** — **LangGraph** controls conditional routing and flow.
- 📄 **Document Ingestion** — **WebBaseLoader** for efficient data loading.
- 🔤 **Embedding Generation** — **HuggingFace all-MiniLM-L6-v2** embeddings.
- 📦 **Vector Storage** — **Astra DB** for fast retrieval.
- 📚 **Wikipedia Integration** — **WikipediaQueryRun** for broad knowledge queries.
- ⚡ **Streaming Responses** — Real-time, interactive answers.

<p align="center">
  <img src="./assets/animated_flow.svg" alt="Animated Flow Diagram" />
</p>

---

## 🛠 Technologies Used

Tool/Library | Purpose
--- | ---
LangChain | Framework for chaining LLM components
LangGraph | State management and routing logic
Groq + Gemma-2 | LLM for query routing and reasoning
HuggingFace | Sentence embeddings (all-MiniLM-L6-v2)
Astra DB | Vector database for domain-specific storage
WikipediaAPIWrapper | General knowledge retrieval
Google Colab | Development and prototyping environment

---

## 📁 Project Structure

```
multi-agent-langgraph/
├── multiagent_1.ipynb   # Core Colab notebook with implementation
├── README.md            # Project documentation
```

---

## 🚀 Getting Started

**Clone**
```bash
git clone https://github.com/khuramshahz/Multi-Agent-Routing-System-with-LangChain-LangGraph.git
cd Multi-Agent-Routing-System-with-LangChain-LangGraph
```

**Install**
```bash
pip install langchain langgraph groq wikipedia-api sentence-transformers astrapy
```

**Configure `.env`**
```bash
GROQ_API_KEY=your_groq_api_key
ASTRA_DB_ENDPOINT=your_astra_db_endpoint
ASTRA_DB_TOKEN=your_astra_db_token
```

**Run**
Open `multiagent_1.ipynb` in **Google Colab** or **Jupyter** and execute the cells.

---

## 🎮 Usage

Input a question — the system will route to the best source:

Example | Route
--- | ---
"What are the latest advancements in prompt engineering?" | 🧠 Astra DB
"Who won the Nobel Prize in 2023?" | 🔍 Wikipedia

**Streaming Output:** Results appear in real-time.

---

## 🤝 Contributing
- Fork the repository  
- Create a feature branch: `git checkout -b feature/YourFeature`  
- Commit: `git commit -m 'Add YourFeature'`  
- Push: `git push origin feature/YourFeature`  
- Open a Pull Request

---

## 📜 License
Licensed under **MIT**. See `LICENSE` for details.

<p align="center">
  <img src="./assets/animated_header.gif" width="720" alt="Animated GIF Banner" />
</p>
