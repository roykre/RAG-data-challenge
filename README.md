# RAG Pipeline Explanation

RAG (Retrieval-Augmented Generation) is a technique that combines document retrieval with generative models to create responses. It utilizes a retrieval model to find relevant documents based on a query, and a generative model (such as GPT) to generate responses grounded in the retrieved documents. This approach helps the system provide accurate, context-based answers by combining information retrieval and generation.

## Project Summary

I was given a data challenge limited to only two days, during which I needed to implement a RAG pipeline. Given a specific case, the system was required to issue a verdict based on the documents I retrieved and the prompt sent to the LLM (Large Language Model).

## Repository Contents

- **presentation/** - This presentation documents the entire process I went through during the project, the challenges I faced, how I solved them, and a performance evaluation.
- **rag_pipeline.ipynb** - The Jupyter Notebook containing the code for the RAG pipeline.

## Requirements

The code in this repository is implemented using Python and PyTorch. Below are the main dependencies required to run the notebook:

- Python 3.7 or higher
- Jupyter Notebook
- haystack-ai  
- datasets>=2.6.1
- sentence-transformers>=2.2.0
- pandas
- os
- getpass

## Author

Roy Kremer
