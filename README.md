# Build RAG From Scratch

This repository provides a hands-on guide to building a Retrieval-Augmented Generation (RAG) system from scratch. It demonstrates how to integrate open-source language models with retrieval frameworks and vector databases to create an end-to-end RAG pipeline.

## 📂 Repository Structure

-`01_Build_RAG_From_Scratch.ipynb` – Introduction to building a basic RAG pipeline

-`02_RAG_with_mistral-llamaindex-hf-offline-with-reranker.ipynb` – Implementation using Mistral models, LlamaIndex, Hugging Face in offline mode, and a reranker

-`03_RAG_with_mistral-llamaindex-hf-offline.ipynb` – Similar to the above but without the reranker component

-`04_RAG_with_mistral-llamaindex-hf-weaviate.ipynb` – Integration with Weaviate vector database

-`data/` – Contains example datasets used in the notebooks

-`requirements.txt` – Lists all Python dependencies required to run the notebooks

## 🚀 Getting Started

### Prerequisites

 Python 3.8 or higher
 Jupyter Notebook
 Gt

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/NewCodeLearner/Build_RAG_From_Scratch.git
   cd Build_RAG_From_Scratch
   ``


2. **Create a virtual environment (optional but recommended):**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use venv\Scripts\activate
   ``


3. **Install the required packages:**

   ```bash
   pip install -r requirements.txt
   ``


4. **Launch Jupyter Notebook:**

   ```bash
   jupyter notebook
   ``


   Open the desired notebook to begin exploring the RAG implementations.

## 🧠 Features

- **Modular Design:* Each notebook focuses on a specific aspect of RAG, allowing for targeted learning and experimentating
- **Offline Capabilities:* Demonstrates how to set up and run RAG pipelines without internet access
- **Integration with Weaviate:* Showcases the use of Weaviate as a vector database for efficient retrieval.
- **Use of Open-Source Models:* Leverages models from Hugging Face and Mistral for generation task.

## 📬 Contact

For any questions or feedback, please reach out via [GitHub Issues](https://github.com/NewCodeLearner/Build_RAG_From_Scratch/isues).

---
