# Data Preprocessing for Machine Learning
This repository contains a seminar paper and an accompanying Jupyter Notebook developed for the course **Data Collection and Preprocessing for Machine Learning**, as part of the MSc program in Artificial Intelligence and Machine Learning at the University of Niš, Faculty of Electronic Engineering.

## Project Overview
The objective of this project is to provide a systematic overview of key text data preprocessing techniques used in natural language processing, along with a practical demonstration of their impact on model performance.

The theoretical part covers:
- Text data quality (document length, vocabulary size, lexical diversity, noise)
- Duplicate removal and data augmentation
- Noise removal (URLs, mentions, hashtags, HTML entities, emoji)
- Text normalization (case folding, Unicode normalization, contraction expansion, spell correction)
- Tokenization
- Stop word removal
- Lemmatization and stemming
- Text representation methods (Bag of Words, TF-IDF, Word2Vec, FastText, BERT)

## Practical Implementation
All preprocessing techniques described in the paper are demonstrated in a Jupyter Notebook using the [**Twitter Toxic Tweets dataset**](https://www.kaggle.com/datasets/umitka/twitter-toxic-tweets).

The task is a binary classification problem (toxic vs. non-toxic tweets). Data augmentation using EDA, backtranslation and T5 paraphrasing is applied to address class imbalance. Model performance is evaluated using:
- Logistic Regression
- Naive Bayes
- Support Vector Machine (Linear)
- Random Forest

Each representation method is combined with all classifiers and compared using accuracy, precision, recall and F1 score. An ablation study demonstrates the contribution of individual preprocessing steps to overall classification performance.

## Repository Structure
- `Teorijski deo/` - Seminar paper (theoretical background)
- `Prakticni deo/` - Jupyter Notebook with experiments and model evaluation

## Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn
- NLTK
- Gensim
- Transformers (HuggingFace)
- Matplotlib
- Seaborn
- Jupyter Notebook

---
This project connects theoretical foundations of text data preprocessing with practical experimentation on a real-world toxic tweet classification task.