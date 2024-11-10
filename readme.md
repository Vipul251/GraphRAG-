# GraphRAG Project: Graph-Based Retrieval-Augmented Generation (RAG) from PDF Documents

## Overview

The GraphRAG project integrates graph-based technologies with Retrieval-Augmented Generation (RAG) to build an advanced information retrieval system. This project leverages a combination of PDF document parsing, knowledge representation through graphs, semantic search using Neo4j, and advanced LLM-powered generation using OpenAI models.

The goal of the project is to automate the extraction and structuring of data from PDF documents, storing the data in a graph database (Neo4j), and utilizing graph-based retrieval techniques to power generative AI applications, such as answering questions and providing summaries based on the data.

## Key Features

- **PDF Document Parsing**: Uses advanced libraries (e.g., LLM Sherpa) to parse and extract structured data from PDF documents.
- **Knowledge Graph with Neo4j**: Data extracted from PDFs is organized into a knowledge graph using Neo4j, facilitating efficient querying and semantic search.
- **Semantic Search**: Integration of Neo4j’s vector indexing to enable semantic search on the graph, allowing for accurate document retrieval based on meaning, not just keywords.
- **Generative AI (RAG)**: Uses OpenAI models for embedding and text generation to generate summaries or answer questions based on the knowledge graph.
- **Data Ingestion & Automation**: Automates the ingestion of new PDF documents and updates the knowledge graph in real-time, ensuring continuous improvement of the knowledge store.

## Technologies Used

- **Python**: The main programming language used for document parsing, data processing, and interaction with Neo4j and OpenAI APIs.
- **LLM Sherpa**: Python library for extracting hierarchical content from PDF documents.
- **Neo4j**: A graph database used to store, index, and query the structured data from the PDF documents.
- **OpenAI (GPT-3/4)**: For generating text responses based on the data in the knowledge graph.
- **Pandas**: Used for structuring and manipulating data before it is ingested into the graph.
- **Neo4j Vector Index**: For semantic search functionality.
- **Flask/Django (optional)**: For building a web interface for interacting with the application.

## Project Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/graphrag-project.git
cd graphrag-project
