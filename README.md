# 🐦 Twitter Entity Sentiment Analysis

This repository contains a machine learning pipeline for sentiment classification using the [Twitter Entity Sentiment Analysis dataset](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis/data) from Kaggle.

We built a complete pipeline including:
- Data preprocessing (cleaning, stemming, stopword removal)
- Feature extraction using TF-IDF
- Model training using Logistic Regression and Random Forest Classifier
- Evaluation on a separate test file

---

## 📊 Dataset

The dataset includes over 70,000 tweets annotated with sentiment labels:
- `Positive`
- `Negative`
- `Neutral`
- `Irrelevant`

Each row contains:
- `Tweet`: The tweet text
- `Sentiment`: The corresponding sentiment label

---


## 🧼 Preprocessing Steps

- Lowercasing
- Removing non-alphabet characters
- Removing English stopwords (`nltk`)
- Stemming with `PorterStemmer`

---

## 🧪 Models and Results

| Model                | Accuracy |
|----------------------|----------|
| Logistic Regression  | 70.26%   |
| Random Forest        | 86.67%   |

---

