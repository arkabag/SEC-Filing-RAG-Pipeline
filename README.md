# RAG Pipeline for SEC Filings QA

This project implements a RAG (Retriever-Generator) Pipeline for Document Question Answering over SEC filings. It utilizes LangChain as the LLM framework, Pinecone as the vector store, and OpenAI's embedding model.

## Installation

To set up the project, install the required dependencies:

```bash
pip install openai
pip install pinecone-client
pip install langchain
pip install tiktoken
pip install pypdf


## Loading SEC Filings
The pipeline processes SEC filings by first loading and splitting the text data. This is demonstrated with financial reports from AXSM and JNJ.

## Setting Up Vector Store
Using Pinecone and OpenAI embeddings, the project sets up a vector store for efficient retrieval of document sections relevant to user queries.

## Adding SEC Filings to Vector Store
SEC filings are added to the vector store, allowing for efficient querying.

## Creating Q&A Chain
The core of the project is the Q&A chain, which leverages LangChain for querying and generating responses.

## Usage
To use the pipeline, invoke the chain with specific questions and company tickers.

