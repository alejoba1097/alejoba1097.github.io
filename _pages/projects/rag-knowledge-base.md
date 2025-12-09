---
title: "RAG Knowledge Base Assistant"
permalink: /projects/rag-knowledge-base/
---

A Retrieval-Augmented Generation (RAG) application to answer domain-specific questions over internal documentation.

[View on GitHub](https://github.com/alejoba1097/knowledge-base-rag)

![RAG Knowledge Base Assistant](/assets/img/rag-knowledge-base.jpeg)

## Overview

- Built a full-stack RAG application to answer domain-specific questions over internal documentation
- Combines document ingestion, indexing, and a generative model
- Delivers contextual, source-grounded answers

## Architecture

- **Backend:** Python FastAPI application with clean architecture (domain, application, infrastructure layers)
- **Frontend:** React + TypeScript single-page application
- **Vector Store:** ChromaDB for document embeddings and similarity search
- **Embeddings:** Sentence Transformers for generating document embeddings
- **Text Extraction:** Tesseract OCR for extracting text from uploaded documents
- **Orchestration:** Docker Compose for local development

## Features

- Upload documents (PDF, images) and automatically extract and index content
- Chat interface to ask questions about uploaded documents
- Source-grounded answers with context from relevant document chunks
- Clean separation of concerns following Domain-Driven Design principles

## Stack

Python, FastAPI, LangChain, ChromaDB, Sentence Transformers, Tesseract OCR, React, TypeScript, Docker

[← Back to Projects](/projects/)

