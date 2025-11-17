🧠 HBS Retrieval-Augmented Generation (RAG) Assignment
Overview

This notebook demonstrates a practical implementation of Retrieval-Augmented Generation (RAG) and Generative AI retrieval workflows, aligned with the Senior Data Scientist, Generative AI Products role at Harvard Business School (Foundry).

The project focuses on designing and evaluating a retrieval pipeline that combines vector-based semantic search, prompt optimization, and context-aware generation for enhanced AI-driven knowledge retrieval.

Objectives

Build a retrieval pipeline that integrates document embeddings, vector storage, and contextual LLM response generation.

Demonstrate understanding of LangChain, OpenAI API, and Pinecone / FAISS vector stores for retrieval.

Evaluate relevance scoring, semantic search precision, and response grounding to mitigate hallucination.

Illustrate how responsible AI principles and data governance (e.g., FERPA/NIST alignment) inform model architecture decisions.

Technical Stack

Languages: Python 3.x

Libraries: LangChain, OpenAI, FAISS, Hugging Face Transformers, pandas, numpy

Vector Database: FAISS or Pinecone (depending on environment setup)

Environment: Jupyter / Google Colab / VS Code Notebook

Cloud Option: AWS S3 (data storage), AWS Bedrock (LLM orchestration)

Core Workflow

Data Ingestion & Preprocessing

Text documents tokenized, chunked, and embedded using sentence-transformers or OpenAI embeddings.

Vector Store Creation

Embeddings indexed in FAISS/Pinecone with metadata for efficient semantic retrieval.

Query & Context Retrieval

User query processed → semantically similar context fetched → appended to prompt.

Generative Response

Context passed into an LLM (GPT-4 or Bedrock Titan) for grounded generation.

Evaluation

Assessed for factual alignment, BLEU/ROUGE scoring, and retrieval precision.

Key Concepts Demonstrated

Retrieval-Augmented Generation (RAG) for enterprise search.

Prompt chaining & optimization to improve contextual grounding.

Evaluation metrics for LLM performance in retrieval workflows.

Responsible AI integration — bias control, content filtering, and governance-ready design.

Author

Quinn Otis, Sr.

Senior Director, Generative AI & Knowledge Systems – The Wharton School, University of Pennsylvania

20+ years experience in AI/ML, data science, and cloud architecture.

AWS Machine Learning Specialty | CompTIA SecurityX | DataX | CloudNetX | ITIL 4 Certified

PhD Candidate – Educational Management, Hampton University (expected Dec 2026)

📧 Contact: qotis@wharton.upenn.edu
