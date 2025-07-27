# 🧠 Natural Language Processing (NLP)

This section provides a high-level overview of core Natural Language Processing (NLP) concepts, useful for both academic understanding and real-world applications.

---

## 📌 Topics Covered

### 🔹 1. Tokenization

Tokenization is the process of splitting text into smaller meaningful components, usually words or sentences. This is the first step in most NLP pipelines.

- **Word Tokenization**: Breaks sentences into individual words.
- **Sentence Tokenization**: Splits text into sentences.
- **Whitespace Tokenization**: Splits based on whitespace characters.
- **Regex Tokenization**: Uses regular expressions for custom splitting.
- **Subword Tokenization**: Used in modern NLP models like BERT for better handling of rare or compound words.

---

### 🔹 2. Stemming

Stemming reduces words to their base or root form by chopping off suffixes. It does not always produce real words but helps in grouping similar terms.

- **Porter Stemmer**: A widely used and classic stemming algorithm.
- **Lancaster Stemmer**: A more aggressive stemmer than Porter.
- **Snowball Stemmer**: A refined version of the Porter stemmer with support for multiple languages.

---

### 🔹 3. Lemmatization

Lemmatization also reduces words to their base form, but unlike stemming, it produces valid dictionary words by considering the context (like part of speech).

- **WordNet Lemmatizer**: Uses WordNet dictionary to find the correct lemma.
- **spaCy Lemmatizer**: A powerful and fast lemmatizer used in production-level NLP tasks.

---

### 🔹 4. Text Vector Encoding Techniques

Text vectorization converts words or documents into numerical representations so that they can be processed by machine learning models.

- **Bag of Words (BoW)**: Represents text by counting word occurrences.
- **TF-IDF (Term Frequency–Inverse Document Frequency)**: Weighs words based on importance and frequency.
- **Word Embeddings**: Captures semantic meaning of words in dense vectors.
  - **Word2Vec**
  - **GloVe**
  - **FastText**
- **Contextual Embeddings**: Provides dynamic representations based on context.
  - **BERT (Bidirectional Encoder Representations from Transformers)**
  - **GPT (Generative Pretrained Transformers)**
  - **Sentence Transformers**

---

## ✅ Requirements

To implement the above techniques, common Python NLP libraries are used, such as:

- NLTK
- spaCy
- scikit-learn
- Hugging Face Transformers (for BERT and GPT-based models)

---

## 📚 References

- [NLTK Documentation](https://www.nltk.org/)
- [spaCy Documentation](https://spacy.io/)
- [Scikit-learn Feature Extraction](https://scikit-learn.org/stable/modules/feature_extraction.html)
- [Hugging Face Transformers](https://huggingface.co/transformers/)

---
