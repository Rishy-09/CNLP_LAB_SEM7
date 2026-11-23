# CNLP Lab — Semester 7

This repository contains the experiments performed for the **Computational Natural Language Processing (CNLP) Lab** during Semester 7.

## Experiments

| Experiment | Topic |
|---|---|
| 1 | CNLP Lab Experiment 1 |
| 2 | CNLP Lab Experiment 2 |
| 3 | CNLP Lab Experiment 3 |
| 4 | CNLP Lab Experiment 4 |
| 5 | CNLP Lab Experiment 5 |
| 6 | GloVe Word Embeddings and N-gram Language Models |
| 7 | IMDb Sentiment Classification |
| 8 | Bengali Abstractive Summarization |

## Experiment 6 — GloVe and N-gram Language Models

This experiment covers:

- GloVe word embeddings implemented from scratch
- Pre-trained GloVe embeddings using Gensim
- Word similarity using cosine similarity
- Bigram language model
- Trigram language model
- Next-word prediction

The experiment is self-contained and does not require any manually uploaded dataset.

## Experiment 7 — IMDb Sentiment Classification

Sentiment classification is performed on the **IMDb Movie Review Dataset** using:

- TF-IDF + Logistic Regression
- LSTM
- Vanilla Transformer
- Pre-trained DistilBERT

The models are compared using **Accuracy, Precision, Recall, F1-score, and Confusion Matrices**.

The experiment was executed on Google Colab using an **NVIDIA Tesla T4 GPU**.

## Experiment 8 — Bengali Abstractive Summarization

This experiment performs Bengali text summarization using the **XL-Sum Bengali dataset**.

Models used:

- mT5 fine-tuned for XL-Sum summarization
- mBART-50 multilingual model

The models are evaluated using multilingual **BERTScore** and qualitative comparison of generated summaries.

Results from the executed experiment:

| Model | BERTScore F1 |
|---|---:|
| mT5 | **0.7244** |
| mBART-50 | 0.5941 |

The experiment was executed on Google Colab using an **NVIDIA Tesla T4 GPU**.

## Repository Structure

```text
Notebooks/
├── Lab1.ipynb
├── Lab2.ipynb
├── Lab_3.ipynb
├── Experiment4/
├── Experiment5/
├── Lab_6.ipynb
├── Lab_7.ipynb
└── Lab_8.ipynb
```

## Tools Used

- Python
- Jupyter Notebook
- Google Colab
- NumPy
- Pandas
- scikit-learn
- PyTorch
- Hugging Face Transformers
- Gensim

Experiments 6, 7, and 8 contain the outputs from their actual executed Colab runs.