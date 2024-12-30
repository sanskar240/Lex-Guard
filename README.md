# Lex-Guard

This pipeline provides an AI-powered compliance assistant that leverages a Retrieval-Augmented Generation (RAG) approach to help businesses efficiently navigate and comply with complex regulations like GDPR, HIPAA, and ISO 27001. By ingesting regulatory documents, indexing them in a vector database, and using AI to generate context-aware answers, the system enables real-time, accurate responses to compliance-related queries. The goal is to reduce manual effort, improve compliance efficiency, and scale with the growing volume of regulatory documents.

# RAG-Based Regulatory Compliance Pipeline

This project demonstrates a simple Retrieval-Augmented Generation (RAG) pipeline for querying and generating compliance-related answers based on regulatory documents (e.g., HIPAA, ISO 27001, and internal policies). The pipeline leverages pre-trained sentence transformers for embedding-based retrieval and T5 for text summarization and answer generation.

## Features

- **Document Ingestion**: Loads and processes regulatory documents such as HIPAA, internal policies, and ISO 27001.
- **Vector-Based Search**: Uses FAISS for fast retrieval of relevant document chunks based on user queries.
- **Answer Generation**: Leverages the T5 model to generate human-readable answers or summaries from relevant document chunks.


## Prerequisites

- Python 3.7 or higher
- `pip` for installing dependencies

## Installation

Clone this repository to your local machine:

```bash
git clone https://github.com/sanskar240/Lex-Guard.git



