# Basic RAG Project

This repository contains a basic implementation of a **Retrieval-Augmented Generation (RAG)** pipeline using LangChain, Chroma db, and LLMs. The goal is to demonstrate how to combine semantic search and large language models for enhanced question answering.

## 📚 Overview

Retrieval-Augmented Generation is a technique that augments LLMs with external knowledge from documents or custom datasets. Instead of relying solely on model parameters, the model retrieves relevant information before generating an answer.

This project:
- Loads and processes documents from a local directory.
- Converts them into vector embeddings.
- Stores them in a Chroma db vector store.
- Uses LangChain to retrieve and generate answers using an LLM.

## 🚀 Features

- Simple and readable code via Jupyter Notebook.
- Document loading using LangChain loaders.
- Embedding generation using OpenAI or Hugging Face models.
- Vector indexing using Chroma db.
- Question answering with retrieval-augmented prompts.

## 🛠️ Requirements

Install the dependencies using pip:
