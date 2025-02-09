# AI-Powered Chatbot with Memory and Multi-Tool Integration

This project implements an intelligent chatbot using **LangChain** and **Groq** models. The chatbot utilizes various tools (DuckDuckGo, Wikipedia, and Arxiv) to gather information and provide accurate answers to user queries.

---

## **Features**
- **ReAct Framework**: Utilizes a custom ReAct prompt to break down questions and interact with available tools.
- **Memory**: The chatbot remembers past conversations for more context-aware responses.
- **Tools**: Integrates external tools like DuckDuckGo, Wikipedia, and Arxiv to fetch information based on user queries.

---

## **Installation**

### 1. Install the necessary packages:
```bash
!pip install -qU langchain langchain_groq langchain_community
!pip install -qU duckduckgo-search arxiv wikipedia
```

### 2. Set up your Groq API Key:
- Sign up on Groq (if you haven't already) and get your API key.
- Add your GROQ_API_KEY in the provided variable.
