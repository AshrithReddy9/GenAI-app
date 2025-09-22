# End-to-End GenAI RAG App

This project implements an end-to-end **Retrieval-Augmented Generation (RAG)** application using **Langchain** and **Llama2**. The app retrieves relevant information from a document store and generates intelligent responses by augmenting the retrieved data with Llama2’s generative AI capabilities.

## Key Features:
- **Document Loading**: Easily load and preprocess various document types (e.g., PDFs).
- **Text Chunking**: Automatically split large text into manageable chunks for efficient retrieval.
- **Embeddings Generation**: Use Hugging Face models to generate vector embeddings for documents.
- **Pinecone Vector Storage**: Store and manage document embeddings in Pinecone’s vector database.
- **RAG Workflow**: Combine retrieved documents with generative AI to produce informative responses.

## Tech Stack:
- **Langchain**: For chaining together retrieval and generation tasks.
- **Llama2**: To handle generative responses.
- **Pinecone**: As the vector store for fast retrieval of relevant documents.
- **Hugging Face**: For generating embeddings from text.
