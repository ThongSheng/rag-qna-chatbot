# rag-qna-chatbot
This Q&amp;A chatbot uses a Retrieval-Augmented Generation (RAG) architecture, integrating LangChain and LangGraph with Google Gemini models to answer questions based on information extracted from specified web pages.

Features
* Retrieval-Augmented Generation (RAG): Enhanced Q&A by combining retrieval and generation.
* Web Content Loading: Fetches and processes data from URLs.
* Text Processing: Chunks documents and creates vector embeddings for search.
* In-Memory Vector Store: Stores and searches embedded data efficiently.
* Google Gemini Integration: Utilizes gemini-2.0-flash for chat and models/embedding-001 for embeddings.
* LangGraph Workflow: Clear, modular, and visualizable application flow.
* LangSmith Tracing: Provides observability for debugging.
