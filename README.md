# RAG-based Question Answering with Llama3

This project demonstrates a Retrieval-Augmented Generation (RAG) pipeline for question answering using the Llama3 language model. The system loads a PDF document, splits it into manageable chunks, embeds these chunks using HuggingFace embeddings, and then utilizes FAISS for efficient document indexing and retrieval. Finally, it answers user queries based on the document content.

## Features

- **Document Loading**: Loads unstructured PDF documents.
- **Text Splitting**: Splits documents into chunks for efficient processing.
- **Embedding Generation**: Uses HuggingFace embeddings to create vector representations of document chunks.
- **Document Indexing and Retrieval**: Utilizes FAISS for fast and accurate retrieval of relevant document chunks.
- **Question Answering**: Uses Llama3 to generate answers to user queries based on the retrieved document content.

## Requirements

- Python 3.7+
- Transformers library
- Langchain community libraries
- FAISS library
- HuggingFace transformers and datasets
- Other dependencies as listed in `requirements.txt`


