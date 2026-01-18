# WeAreDevelopers World Congress 2025 - GenAI Masterclass

Workshop materials for "From Zero to Hero: How to put GPT LLMs & friends into your applications - Generative AI in Action"

## Description

A hands-on masterclass teaching how to integrate Generative AI and Large Language Models into applications. Covers key architectural patterns including In-Context Learning, RAG, Structured Output, Tool Calling, and ReAct.

## Topics Covered

- Human language as interface for software (prompts as UI)
- LLM basics with Python and .NET APIs
- RAG (Retrieval-Augmented Generation)
- Function/Tool Calling
- Structured Output
- ReAct (Reasoning & Acting) agents
- Speech-to-text integration

## Repository Structure

```
Demos/                    # Live demonstration code
  Hello World/            # Basic LLM integration (LangChain, Semantic Kernel, OpenAI SDK)
  Function Calling/       # Tool calling examples (LangGraph, Semantic Kernel)
  Information Extraction/ # Voice orders, flight query extraction
  RAG/                    # Embeddings, vector DB, retrieval patterns
  ReAct/                  # Barebones ReAct agent implementation

Hands-on/                 # Workshop exercises with solutions
  chat/                   # Simple chat lab
  function_calling/       # Tool calling lab
  structured_output/      # Extraction lab
  vector_db-and-rag/      # RAG lab
```

## Tech Stack

- **Python**: LangChain, LangGraph, OpenAI SDK, Streamlit
- **.NET/C#**: Semantic Kernel, OpenAI SDK
- **Jupyter Notebooks** for demos and labs

## Prerequisites

- Python 3.10+
- .NET 8.0+
- OpenAI API key (or Azure OpenAI)

## Setup

1. Clone the repository
2. For Python projects: `pip install -r requirements.txt` in respective folders
3. For .NET projects: Open `gen-ai-workshop.sln` in Visual Studio
4. Copy `.env.example` to `.env` and add your API keys

## License

MIT
