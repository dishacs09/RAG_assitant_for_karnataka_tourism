# RAG Pipeline on Karnataka Tourism Website

This repository contains a **Retrieval-Augmented Generation (RAG) pipeline** built using **LangChain**, **ChromaDB**, and the **OpenAI API**.  
The pipeline retrieves relevant information scraped from the **Karnataka Tourism website** and generates accurate, context-aware answers.

---

## What is RAG?

**Retrieval-Augmented Generation (RAG)** combines:
- **Information Retrieval** to fetch relevant documents
- **Large Language Models (LLMs)** to generate accurate responses

This enables the model to answer questions using **real website data** instead of relying only on pre-trained knowledge.

---

## 🔍 What I Implemented in This RAG Pipeline

### 1️⃣ Web Scraping Karnataka Tourism Website
- Scraped tourism-related content from the Karnataka Tourism website
- Collected information on tourist destinations, travel details, and cultural heritage
- Used the scraped data as the knowledge base

### 2️⃣ Data Cleaning & Text Splitting
- Cleaned raw text to remove HTML and unnecessary noise
- Split content into smaller chunks to improve retrieval accuracy

### 3️⃣ Generating Embeddings
- Converted text chunks into vector embeddings using the OpenAI API
- Embeddings capture semantic meaning, enabling context-aware retrieval

### 4️⃣ Vector Storage & Retrieval
- Stored embeddings in **ChromaDB**
- Retrieved the most relevant tourism content using similarity search for each user query

---

## Outcome
- Built a domain-specific question-answering RAG pipeline  
- Reduced hallucinations by grounding responses in retrieved website content  
- Demonstrated an end-to-end RAG workflow using real-world data

---

<img width="1021" height="315" alt="Screenshot 2026-01-07 at 4 14 41 PM" src="https://github.com/user-attachments/assets/deaa56cd-84e9-4b78-9e20-b20537f0ba6d" />

