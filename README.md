# AI-Powered RAG Assistant

An AI-powered Retrieval-Augmented Generation (RAG) assistant built using n8n, OpenAI, and Supabase Vector Database with conversational memory and semantic search capabilities.

## Features

* Document ingestion from Google Drive
* OpenAI embeddings generation
* Semantic search using vector database
* Conversational memory support
* AI-powered contextual question answering
* Dockerized deployment setup

## Workflow Architecture

Google Drive → Data Loader → Text Splitter → OpenAI Embeddings → Supabase Vector Store → AI Agent + Memory

## Tech Stack

* n8n
* OpenAI API
* Supabase Vector Database
* PostgreSQL / Simple Memory
* Docker
* Vector Embeddings
* Semantic Search
* RAG Architecture

## Docker Deployment

Run the project using Docker:

```bash id="m1t9qv"
docker compose up -d
```

Open in browser:

```txt id="n4x7pr"
http://localhost:5678
```

## Project Purpose

This project demonstrates how modern AI assistants retrieve contextual information from custom knowledge bases using Retrieval-Augmented Generation (RAG), vector embeddings, semantic search, and conversational memory workflows.
