# AI Knowledge Engine using n8n (RAG)

This project demonstrates a Retrieval-Augmented Generation (RAG) system built using n8n workflows and a backend API.

## Overview
The system processes document-based knowledge (Rules of Golf) and allows users to query it in natural language. It retrieves relevant context and generates grounded responses using an LLM.

## Features
- Document-based Q&A using RAG
- n8n workflow orchestration
- API-based retrieval system
- Context-grounded answers
- Scalable pipeline (can be extended to policy documents, research reports, etc.)

## Use Case Extension
This system can be adapted for:
- Policy document analysis
- Research report summarization
- Knowledge retrieval systems like PDRC

## Tech Stack
- n8n (workflow automation)
- FastAPI (backend)
- FAISS (vector database)
- Open-source LLM

## Future Improvements
- Policy brief generation
- Executive summaries
- Multi-language support (English/Hindi)
