# Comprehensive NLP and LLM Study Repository

![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![Status](https://img.shields.io/badge/Status-Active-success.svg)

Welcome to the **Comprehensive NLP and LLM Study Repository**. This project serves as an organized, professional learning and implementation space for Natural Language Processing (NLP), Deep Learning, and Large Language Models (LLMs). The repository captures the evolution of NLP, guiding you from classical probabilistic models to modern contextual representations and complex application tasks.

## Project Architecture & Structure

The repository is divided into distinct, logically isolated modules:

```text
llm/
├── deep_learning_models/       # Core neural network architectures for sequence data
│   ├── lstm.ipynb              # Long Short-Term Memory networks
│   └── recurrent_neural_network.ipynb # Recurrent Neural Networks
├── llm_models/                 # Foundational NLP theories and language models
│   ├── probabilistic_models/   # HMM, MaxEnt, and N-gram statistical models
│   └── text_representation/    # From Bag-of-Words and TF-IDF to Word Embeddings
├── nlp_tasks/                  # Applied NLP tasks and end-to-end pipelines
│   ├── morphological_analysis.ipynb
│   ├── question_answering_bert.ipynb
│   ├── question_answering_gpt.ipynb
│   ├── sentiment_analysis.ipynb
│   └── text_classification.ipynb
├── .venv/                      # Python Virtual Environment
└── README.md                   # Project Overview (You are here)
```

## Key Modules Overview

### 1. `nlp_tasks/`
Contains complete implementations of widespread NLP tasks. Highlights include **Sentiment Analysis**, advanced **Question Answering** leveraging transformer architectures like BERT and GPT, and foundational text classification techniques.

### 2. `deep_learning_models/`
Delves into the deep learning architectures that revolutionized sequence processing. Notebooks here break down the inner workings of **RNNs** and **LSTMs**, emphasizing their capability to retain contextual memory.

### 3. `llm_models/`
The backbone of language modeling theory.
- **`probabilistic_models/`**: Explores the statistical roots of NLP (Markov models, N-Grams, Maximum Entropy).
- **`text_representation/`**: A journey through text vectorization, transitioning from sparse representations (Bag of Words, TF-IDF) to dense semantic captures (Word Embeddings).

## Installation and Setup

To run the notebooks successfully, it is highly recommended to use the provided virtual environment or create a new one to manage dependencies.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/kadir465/llm_all_models.git
   cd llm_all_models
   ```

2. **Activate the Virtual Environment:**
   - **Windows:**
     ```bash
     .\.venv\Scripts\activate
     ```
   - **Linux/Mac:**
     ```bash
     source .venv/bin/activate
     ```

3. **Install Dependencies:**
   *(Ensure you have Jupyter installed alongside ML frameworks like PyTorch/TensorFlow, Scikit-learn, HuggingFace Transformers, and NLTK).*
   ```bash
   pip install jupyter torch transformers scikit-learn pandas numpy
   ```

## Getting Started

We recommend following this learning trajectory if you are new to the repository:
1. Start with **`llm_models/text_representation/`** to understand how text becomes data.
2. Review **`llm_models/probabilistic_models/`** to see how classical statistics parse sequential data.
3. Move to **`deep_learning_models/`** for modern sequence learning networks.
4. Conclude with **`nlp_tasks/`** to see these representations and architectures applied to real-world problems.

## Contributing
Contributions, issues, and feature requests are welcome. Feel free to check the issues page if you want to contribute.

## License
This project is open-source and available under the MIT License.
