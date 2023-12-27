# SEC Filing RAG Pipeline

The SEC Filing RAG (Retrieve, Answer, Generate) Pipeline is a versatile tool designed for processing and extracting information from SEC filings. It leverages various libraries and modules to enable efficient document retrieval, question-answering, and text analysis.

## Table of Contents
- [Initial Setup](#initial-setup)
- [Importing Text Processing Modules](#importing-text-processing-modules)
- [Loading and Processing Financial Reports](#loading-and-processing-financial-reports)
- [Setting Up the Vector Store](#setting-up-the-vector-store)
- [Adding SEC Filings to the Vector Store](#adding-sec-filings-to-the-vector-store)
- [Create Document Q&A Chain With LLM Framework](#create-document-qa-chain-with-llm-framework)
- [Document Q&A Queries By Company](#document-qa-queries-by-company)

---

## Initial Setup

### Step 1: Install Dependencies
Install essential libraries such as openai, pinecone-client, langchain, tiktoken, and pypdf to enable language model integration, vector storage, and PDF processing capabilities.

## Importing Text Processing Modules

### Step 2: Importing Text Processing Modules
Import langchain modules, including RecursiveCharacterTextSplitter and PyPDFLoader, for text chunking and PDF document loading.

## Loading and Processing Financial Reports

### Step 3: Loading and Processing Financial Reports
Load and process financial reports from Axsome Therapeutics Inc. (AXSM) and Johnson & Johnson (JNJ).

## Setting Up the Vector Store

### Step 4: Setting Up the Vector Store
Establish a vector store using Pinecone and OpenAI embeddings for efficient document vectorization.

## Adding SEC Filings to the Vector Store

### Step 5: Adding SEC Filings to the Vector Store
Add SEC filings from AXSM and JNJ to the vector store under respective namespaces for structured and searchable data.

## Create Document Q&A Chain With LLM Framework

### Step 6: Create Document Q&A Chain With LLM Framework
Set up a question-answering chain using LangChain's capabilities, integrating chat models, embeddings, and prompt templates.

## Document Q&A Queries By Company

### Step 7: Document Q&A Queries By Company
Perform specific queries on financial reports of companies like AXSM and JNJ using the Q&A chain.
