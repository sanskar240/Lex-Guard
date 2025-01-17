# Lex-Guard

This pipeline provides an AI-powered compliance assistant that leverages a Retrieval-Augmented Generation (RAG) approach to help businesses efficiently navigate and comply with complex regulations like GDPR, HIPAA, and ISO 27001. By ingesting regulatory documents, indexing them in a vector database, and using AI to generate context-aware answers, the system enables real-time, accurate responses to compliance-related queries. The goal is to reduce manual effort, improve compliance efficiency, and scale with the growing volume of regulatory documents.

# RAG-Based Regulatory Compliance Pipeline

This project demonstrates a simple Retrieval-Augmented Generation (RAG) pipeline for querying and generating compliance-related answers based on regulatory documents (e.g., HIPAA, ISO 27001, and internal policies). The pipeline leverages pre-trained sentence transformers for embedding-based retrieval and T5 for text summarization and answer generation.

## Features

- **Document Ingestion**: Loads and processes regulatory documents such as HIPAA, internal policies, and ISO 27001.
- **Vector-Based Search**: Uses FAISS for fast retrieval of relevant document chunks based on user queries.
- **Answer Generation**: Leverages the T5 model to generate human-readable answers or summaries from relevant document chunks.


## Workflow

<img width="671" alt="Screenshot 2025-01-18 at 3 28 05 AM" src="https://github.com/user-attachments/assets/5f597bd8-9d6d-4367-87f0-fbe658c24f9e" />




## In Action

<img width="1072" alt="Screenshot 2025-01-18 at 1 49 05 AM" src="https://github.com/user-attachments/assets/25c3b012-4fa0-4452-9e50-45d84971b40b" />

<img width="1075" alt="Screenshot 2025-01-18 at 1 50 23 AM" src="https://github.com/user-attachments/assets/8a4dd353-61cb-4221-adca-f35df87ed432" />


<img width="1086" alt="Screenshot 2025-01-18 at 1 50 59 AM" src="https://github.com/user-attachments/assets/865b890b-e3a0-4ee8-b181-a1278075dcae" />




## Prerequisites

- Python 3.7 or higher
- `pip` for installing dependencies

## Installation

Clone this repository to your local machine:

```bash
git clone https://github.com/sanskar240/Lex-Guard.git



