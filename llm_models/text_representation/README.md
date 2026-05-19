# Text Representation

Text representation is a crucial preprocessing step in NLP. Before algorithms can process natural language, the text must be mathematically represented as vectors. This directory covers various methods from sparse representations to dense semantic embeddings.

## Sub-Modules

### 1. `bag_of_words/`
The Bag of Words (BoW) model represents text by counting the frequency of words, ignoring order and grammar.
- **`bag_of_words_implementation.ipynb`**: Core implementation logic of BoW from scratch.
- **`bag_of_words_imdb.ipynb`**: Application of BoW on the IMDB sentiment analysis dataset (`imdb.csv`).

### 2. `n_gram/`
- **`n_gram.ipynb`**: Extends BoW by considering sequences of *N* words together (e.g., bigrams, trigrams), helping to retain some local contextual and word-order information.

### 3. `tf_idf/`
Term Frequency-Inverse Document Frequency (TF-IDF) penalizes highly frequent words and boosts rare, informative words.
- **`tf_idf_implementation.ipynb`**: Step-by-step implementation of the TF-IDF statistical measure.
- **`tf_idf_sms_spam.ipynb`**: Practical application of TF-IDF using the `spam.csv` dataset for spam detection.

### 4. `word_embedding/`
Unlike sparse methods, word embeddings provide dense, low-dimensional vectors that capture semantic similarities between words.
- **`word_embedding_implementation.ipynb`**: Introduction to creating dense word vectors.
- **`word_embedding_imdb.ipynb`**: Application of word embeddings on the IMDB dataset.

## Why Text Representation Matters
The choice of text representation dramatically affects model performance, computational efficiency, and semantic understanding. Reviewing these notebooks provides a solid transition from simple counting to deep semantic learning.
