# AI Knowledge Engine using n8n (RAG)

This project demonstrates a Retrieval-Augmented Generation (RAG) system built using n8n workflows and a backend API.

## Overview
The system processes document-based knowledge (Rules of Golf) and allows users to query it in natural language. It retrieves relevant context and generates responses based on that context using an LLM.

## Features

- Document-based question answering using RAG  
- Vector storage and similarity search using Supabase (pgvector)  
- OpenAI embeddings and response generation  
- n8n workflows for handling query and response flow  
- Generation of structured outputs such as summaries and brief-style responses  
- Can be extended to other document types like research or policy content  
