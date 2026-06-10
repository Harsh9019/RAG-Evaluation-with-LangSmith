# 🔍 RAG Evaluation with LangSmith

A comprehensive project demonstrating how to evaluate Retrieval-Augmented Generation (RAG) applications using LangSmith, OpenAI, and LangChain.

This project covers the complete RAG evaluation workflow, including dataset creation, chatbot evaluation, retrieval quality assessment, response correctness validation, and grounding analysis using LLM-as-a-Judge techniques.

## 🚀 Features

* Build and evaluate RAG applications
* Create evaluation datasets using LangSmith
* Measure chatbot response quality
* Evaluate retrieval performance
* Assess answer correctness and relevance
* Check response groundedness
* Compare different OpenAI models
* End-to-end RAG evaluation pipeline

## 🛠️ Technologies Used

* Python
* LangChain
* LangSmith
* OpenAI GPT-4o Mini
* OpenAI GPT-4 Turbo
* OpenAI Embeddings
* Vector Stores
* RAG Architecture

## 📊 Evaluation Metrics

### 1. Correctness

Measures whether the generated response matches the expected answer.

### 2. Relevance

Checks whether the response directly addresses the user's question.

### 3. Groundedness

Verifies that the response is supported by retrieved documents and does not contain hallucinations.

### 4. Retrieval Relevance

Evaluates whether the retrieved documents are relevant to the user query.

## 📂 Project Workflow

1. Create evaluation datasets
2. Build a chatbot/RAG pipeline
3. Generate responses
4. Run automated evaluations
5. Analyze performance metrics
6. Compare model outputs

## 🔍 RAG Pipeline

```text
User Query
     ↓
Retriever
     ↓
Relevant Documents
     ↓
LLM (GPT-4o Mini / GPT-4 Turbo)
     ↓
Generated Answer
     ↓
LangSmith Evaluation
     ↓
Performance Metrics
```

## 📈 What This Project Demonstrates

* LLM-as-a-Judge evaluation
* Automated RAG benchmarking
* Dataset-driven testing
* Retrieval quality assessment
* Hallucination detection
* Production-ready evaluation practices

## ▶️ Getting Started

### Clone the Repository

```bash
git clone https://github.com/your-username/rag-evaluation.git
cd rag-evaluation
```

### Install Dependencies

```bash
pip install langchain
pip install langsmith
pip install openai
pip install python-dotenv
```

### Configure Environment Variables

```env
OPENAI_API_KEY=your_openai_api_key
LANGSMITH_API_KEY=your_langsmith_api_key
LANGSMITH_TRACING=true
```

### Run the Notebook

```bash
jupyter notebook rag-evaluation.ipynb
```

## 🎯 Learning Outcomes

This project helped in understanding:

* Retrieval-Augmented Generation (RAG)
* LangSmith Evaluation Framework
* AI System Benchmarking
* Prompt Engineering
* Vector Search & Retrieval
* LLM Evaluation Metrics
* Hallucination Detection

## 👨‍💻 Author

Harsh Thakre

M.Tech | AI/ML Engineer

Passionate about Generative AI, RAG, LangChain, Machine Learning, and AI Evaluation Systems.

## ⭐ Support

If you found this project useful, please consider giving it a star on GitHub.
