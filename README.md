# 🧠 Deep Agents Learning Lab

An educational implementation of **Deep Agents** built with **LangGraph**, **DeepAgents**, and **Streamlit**.

This project was created while learning from **Krish Naik's Deep Agents tutorials**. The goal was to understand how Deep Agents work internally by implementing the concepts myself—not to claim originality or present a new framework.

The project combines the concepts from multiple notebooks into a single interactive Streamlit application.

---

## 📚 Disclaimer

> **Educational Purpose Only**

This repository is created solely for learning and experimentation.

The implementation is based on concepts explained in Krish Naik's Deep Agents tutorial series. I wrote this code while following along and exploring the framework to deepen my understanding.

I do **not** claim ownership of the underlying ideas or architecture presented in the tutorials.

---

# Features

This application demonstrates many Deep Agent capabilities in one place.

- ✅ Deep Agent creation
- ✅ Custom system prompts
- ✅ Tavily web search tool
- ✅ Planning with Todo Lists
- ✅ Virtual File System
- ✅ AGENTS.md Context Engineering
- ✅ Agent Skills
- ✅ Thread Memory
- ✅ Multiple Storage Backends
- ✅ Subagents
- ✅ Structured Output
- ✅ Interactive Streamlit UI

---

# Project Structure

```
.
├── streamlit_app.py
├── requirements.txt
├── AGENTS.md

├── 1basicDeepAgent.ipynb
├── 2contextEngineering.ipynb
├── 3backends.ipynb
└── 4subagents.ipynb
```

The notebooks demonstrate each concept individually, while the Streamlit app integrates them into a single application.

---

# Concepts Covered

## 1. Deep Agent Basics

- Creating Deep Agents
- Custom system prompts
- Tool integration
- Tavily web search

---

## 2. Context Engineering

- AGENTS.md
- Memory loading
- Skills
- Thread-based conversation memory

---

## 3. Storage Backends

The application supports three backend types:

### StateBackend

- In-memory
- Thread-specific
- Virtual file system

### FilesystemBackend

- Stores files on disk
- Virtual filesystem rooted in project directory

### StoreBackend

- Shared memory across conversations
- Persistent storage

---

## 4. Subagents

The application includes two example subagents:

### Research Agent

Performs deeper research using web search.

### Structured Researcher

Returns structured outputs including:

- Summary
- Confidence score
- Sources

---

# Technologies Used

- Python
- Streamlit
- LangGraph
- DeepAgents
- LangChain
- OpenAI
- Groq
- Tavily Search
- Pydantic

---

# Installation

Clone the repository

```bash
git clone https://github.com/<your-username>/deepagents-learning-lab.git

cd deepagents-learning-lab
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

# Environment Variables

Create a `.env` file.

```env
OPENAI_API_KEY=your_key

GROQ_API_KEY=your_key

TAVILY_API_KEY=your_key
```

---

# Run

```bash
streamlit run streamlit_app.py
```

---

# What You Can Explore

The Streamlit interface allows you to experiment with:

- Different LLM providers
- Different storage backends
- AGENTS.md context
- Agent Skills
- Thread memory
- Planning
- Web Search
- Subagents
- Structured outputs

---

# Learning Resources

This project was built while learning from:

- Krish Naik's Deep Agents tutorial series
- LangGraph documentation
- DeepAgents documentation

I highly recommend checking out the original resources for a deeper understanding.

---

# Acknowledgements

Special thanks to **Krish Naik** for creating the Deep Agents tutorial series that inspired this learning project.

Thanks to the teams behind:

- LangGraph
- LangChain
- DeepAgents
- Streamlit
- Tavily

for building these amazing open-source tools.

---

# Future Improvements

Some ideas I may explore in the future:

- More custom tools
- Multi-agent collaboration
- RAG integration
- Local LLM support
- Authentication
- Better UI/UX
- Deployment

---

# License

This repository is intended for educational purposes.

Please refer to the licenses of the libraries used in this project before using any part of this implementation in production.

---

⭐ If this repository helps someone who is also learning Deep Agents, consider giving it a star.