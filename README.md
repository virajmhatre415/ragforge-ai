# RAGForge

Build trustworthy document AI applications faster.

RAGForge is an open-source toolkit for building document-grounded AI assistants. 
It helps developers ingest documents, retrieve relevant context, generate answers, 
and show the sources behind each response.

## What it does

- Upload and process PDF documents
- Split documents into retrieval-ready chunks
- Generate vector embeddings and store them in a vector database
- Answer user questions using retrieved document context
- Display source references with each answer
- Provide a simple Streamlit interface for testing RAG workflows

## Who it is for

RAGForge is for developers, data teams, and startups building internal knowledge assistants, 
document Q&A tools, support copilots, or AI search applications.

## Current status

The open-source toolkit is under active development.

Planned hosted capabilities include managed deployments, shared team workspaces, 
document management, evaluation workflows, and production observability.

## Quick start

```bash
git clone [https://github.com/YOUR-GITHUB-USERNAME/ragforge-ai.git](https://github.com/YOUR-GITHUB-USERNAME/ragforge-ai.git)
cd ragforge-ai
pip install -r requirements.txt
streamlit run app.py
```

## Tech stack

- Python
- Streamlit
- LangChain
- ChromaDB
- OpenAI-compatible LLM providers

## Contributing

Issues, feature requests, and pull requests are welcome.

## License

MIT
