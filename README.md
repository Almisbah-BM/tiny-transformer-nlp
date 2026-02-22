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

## Project Goal
To understand how mathematical structures power AI systems used in scientific discovery,
including applications in health data analysis, knowledge extraction, and predictive modeling.

## Author
Misbahu Bashir Mustapha  
B.Sc. Computer Science  
Interested in AI for Science, Data Science, and Mathematical Modeling.
