# 📚 N-Gram Language Models

This project implements classic **statistical language models** from scratch, using unigram and n-gram probabilities to analyze, generate, and correct text in both English and Japanese.

---

## 📓 Notebooks Included

| Notebook | Focus | Description |
|----------|-------|-------------|
| `Unigram_LM.ipynb` | 📖 English Unigram Model | Builds a unigram language model for English text using word frequencies. Includes generation of simple text samples based on learned probabilities. |
| `Unigram_LM_Japanese.ipynb` | 🇯🇵 Japanese Unigram Model | Constructs a unigram model for Japanese text. Handles tokenization and frequency distribution for Japanese character sequences. |
| `Ngram_Text_Correction.ipynb` | 🛠️ N-Gram Based Text Correction | Uses bigrams and trigrams to perform simple spell correction. Selects the most probable sentence reconstruction using n-gram likelihoods. |

---

## 🔍 Key Features

- Train unigram and n-gram models from scratch
- Tokenization and smoothing support
- Text generation using learned distributions
- Text correction using n-gram likelihoods
- Works for both English and Japanese datasets

---

## 🛠 Technologies Used

- Python
- NLTK (for English tokenization)
- MeCab or other tokenizer (for Japanese, optional)
- NumPy, collections
- Jupyter Notebooks

---

## 📁 Project Structure

ngram-language-models/
├── Unigram_LM.ipynb
├── Unigram_LM_Japanese.ipynb
├── Ngram_Text_Correction.ipynb
└── README.md

---

## ⭐ Purpose

This project was created to demonstrate a foundational understanding of how traditional language models work under the hood — before deep learning took over. It explores how statistical properties of text can be used for generation, prediction, and correction.

