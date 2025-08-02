# 🤖 Multi-Agent Routing System with LangChain + LangGraph

> An AI-powered system that intelligently routes user queries to either a vector-based internal knowledge source or Wikipedia, using LangChain, LangGraph, Groq LLMs, and Astra DB.

---

## 🌟 Project Overview

This project implements a **multi-agent system** using **LangGraph** and **LangChain** to dynamically answer user questions based on their content. The system makes intelligent decisions about **which data source** is most appropriate:

- 🔍 **Wikipedia** for general knowledge queries
- 🧠 **Vector Store (Astra DB)** for domain-specific information (AI agents, prompt engineering, LLM attacks, etc.)

Built with modular design and real-world production use cases in mind.

---

## 🧠 Key Features

- ✅ **Question Routing Logic** powered by `Groq's Gemma-2 9B Instruct` LLM  
- ✅ **LangGraph State Machine** to manage flow and conditional paths  
- ✅ **Document Loading** using `WebBaseLoader`  
- ✅ **Embeddings** generated with `HuggingFace - all-MiniLM-L6-v2`  
- ✅ **Vector Store** setup with `Astra DB`  
- ✅ **Wikipedia Integration** with `WikipediaQueryRun`  
- ✅ **Streaming Response Support**  

---

## 🔧 Technologies Used

| Tool / Library       | Purpose                                  |
|----------------------|------------------------------------------|
| LangChain            | Framework for chaining LLM components    |
| LangGraph            | State management and routing             |
| Groq + Gemma-2       | LLM for routing logic                    |
| HuggingFace          | Sentence embeddings                      |
| Astra DB             | Vector database for long-term storage    |
| WikipediaAPIWrapper  | Web search for general queries           |
| Colab (Google)       | Development and prototyping              |

---

## 📁 Project Structure

```bash
📦multi-agent-langgraph
 ┣ 📜 multiagent_1.ipynb       # Main Colab notebook
 ┣ 📜 README.md                # Project documentation
