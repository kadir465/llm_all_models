# Probabilistic Models

This directory contains implementations of classical probabilistic and statistical models used in Natural Language Processing for sequence prediction, tagging, and generation.

## Contents

- **`hidden_markov_model.ipynb`**: Implementation of Hidden Markov Models (HMM). Essential for tasks like Part-of-Speech (POS) tagging and Named Entity Recognition (NER), where predictions depend on unobserved (hidden) states.
- **`maximum_entropy_model.ipynb`**: Demonstrates the Maximum Entropy (MaxEnt) classifier, a probabilistic model often used for text classification and sequence labeling tasks that do not assume feature independence (unlike Naive Bayes).
- **`n_gram_model.ipynb`**: A probabilistic sequence model that predicts the next item in a sequence based on the `(n-1)` preceding items. Fundamental for basic text generation and language modeling.

## Learning Objectives

By exploring these notebooks, you will understand:
- How probabilities shape language understanding.
- The transition from naive statistical models to Markov-based assumptions.
- Traditional sequence labeling techniques that predated deep learning.
