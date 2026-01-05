# COVID-19 Vaccine Sentiment Analysis and Prediction

An applied machine learning and natural language processing project
analyzing public sentiment toward COVID-19 vaccines and exploring
predictive relationships between sentiment signals and real-world
variables.

This repository implements data collection, preprocessing, sentiment
modeling, and exploratory prediction using social media text data.

---

## 30-Second Quick View

Public sentiment toward COVID-19 vaccination is an important indicator
of acceptance, hesitancy, and public opinion during and after the global
pandemic. This project:

- Collects and preprocesses vaccine-related social media text (e.g.,
  Twitter data)
- Extracts sentiment features using NLP techniques
- Builds sentiment models (e.g., polarity classification)
- Explores predictive relationships between sentiment signals and
  external variables (e.g., case counts or vaccine uptake)

## Core Skills Demonstrated
Natural Language Processing · Sentiment Analysis · Text Classification ·
Feature Engineering · Applied Machine Learning · Exploratory Data Analysis
---

## Dataset Sources

Tweets dataset is from Panacea Lab includes tweets with key
wordscontaining “COVID-19”or“vaccine” from December1,2020
to October 31, 2021. In this work

> Due to data size, raw tweet datasets are not included
> in this repository. 

---

## Methods

### 1. Data Collection and Preprocessing

- Collect tweets using Twitter API or load from downloaded datasets
- Clean and normalize text (remove duplicates, strip noise, tokenize)
- Handle encoding, language filtering, and date alignment

### 2. Sentiment Feature Extraction

- Generate text features using vectorization techniques such as:
  - Bag-of-Words
  - TF-IDF
  - CountVectorizer
- Optionally use pretrained embeddings (e.g., BERT variants)

### 3. Sentiment Modeling

- Train classification models for sentiment polarity (positive,
  neutral, negative):
  - Logistic Regression
  - Support Vector Machines (SVM)
  - Naïve Bayes
  - Deep learning models (e.g., LSTM / transformer) if used

### 4. Exploratory Prediction

- Use sentiment time series as features to model external targets
  (case counts, vaccination rates, etc.)
- Evaluate using appropriate metrics (accuracy, precision, recall)

---

## Evaluation Strategy

- Classification performance evaluated by:
  - Accuracy
  - F1 Score
  - Confusion Matrix
- Sentiment trend analysis over time
- Optional correlation or regression exploration with external targets

---


## Project Scope
This repository demonstrates:

- Natural language processing for sentiment analysis
- Text vectorization and classification modeling
- Exploratory predictive analysis using sentiment signals
- Applied machine learning workflow



