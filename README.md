# RAG Pipeline Explanation

RAG (Retrieval-Augmented Generation) is a technique that combines document retrieval with generative models to create responses. It utilizes a retrieval model to find relevant documents based on a query, and a generative model (such as GPT) to generate responses grounded in the retrieved documents. This approach helps the system provide accurate, context-based answers by combining information retrieval and generation.

## Project Summary

In this project, I developed a Retrieval-Augmented Generation (RAG) pipeline designed to answer legal questions based on previous verdicts. The pipeline integrates document retrieval and natural language generation to provide informed responses. The time allocated to me for this work was only two days, which made the challenge even more intense and rewarding.

## Repository Contents

- **presentation.pdf** - This presentation documents the entire process I went through during the project, the challenges I faced, how I solved them, and a performance evaluation.
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
