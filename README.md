# Tiny Transformer NLP Project

## Overview
This project implements a minimal Transformer-based language model from first principles using Python and PyTorch.  
The goal is to demonstrate the mathematical foundations behind modern Natural Language Processing systems.

Rather than using large pretrained models, the architecture was built step-by-step to show how linear algebra,
probability theory, and optimization enable machines to learn structure from text.

## Key Concepts Demonstrated
- Tokenization of raw scientific text into discrete symbols
- Word embeddings as vector space representations (Linear Algebra)
- Self-attention mechanism using similarity (Dot Products)
- Softmax transformation to obtain probability distributions
- Training with Cross-Entropy Loss (Information Theory)
- Optimization using Gradient Descent
- Evaluation using Perplexity

## Mathematical Insight
The attention mechanism is implemented as:

Attention(Q, K, V) = softmax(QKᵀ / √d)V

This shows how relationships between words can be modeled using matrix operations and probability distributions.

## Tools Used
- Python
- PyTorch
- NumPy
- Scikit-learn (for visualization)

  
## How to Run the Project

1. Open the notebook:
   Tiny_Transformer_Project.ipynb

2. Run all cells sequentially in Google Colab or Jupyter Notebook.

3. The notebook will:
   - Tokenize the dataset
   - Train a minimal Transformer model
   - Compute loss and perplexity
   - Visualize learned word embeddings

     
## Scientific Motivation

Modern scientific knowledge exists largely in unstructured text such as
medical reports and research literature. This project explores how
mathematical models of language can extract structure from such data.

Understanding these mechanisms is essential for applying AI to
scientific challenges such as disease modeling, knowledge discovery,
and data-driven decision making.

## Project Goal
To understand how mathematical structures power AI systems used in scientific discovery,
including applications in health data analysis, knowledge extraction, and predictive modeling.

## Author
Misbahu Bashir Mustapha  
B.Sc. Computer Science  
Interested in AI for Science, Data Science, and Mathematical Modeling.
