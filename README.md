DATASET: https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews

# 📊 Sentiment Analysis of Amazon Reviews

This project performs sentiment analysis on Amazon Fine Food Reviews using VADER and RoBERTa to compare rule-based and transformer-based approaches.

---

## 🚀 Overview

The goal of this project is to analyze customer sentiment from textual reviews and compare the performance of two different NLP techniques:
- **VADER** (fast, rule-based)
- **RoBERTa** (context-aware deep learning model)

---

## 📂 Dataset

- Amazon Fine Food Reviews dataset
- Contains user reviews, ratings, and metadata

---

## ⚙️ Features

- Data cleaning and preprocessing
- Handling missing values
- Exploratory Data Analysis (EDA)
- Sentiment analysis using VADER
- Sentiment analysis using RoBERTa (on sample data)
- Comparison of model outputs
- Visualization using graphs

---

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- NLTK (VADER)
- Hugging Face Transformers (RoBERTa)
- Matplotlib, Seaborn

---

## 📈 Key Insights

- VADER is fast and works well on large datasets
- RoBERTa captures deeper context but is computationally expensive
- Some reviews show mismatch between rating and sentiment
- Models struggle with sarcasm and mixed sentiment

---

## ▶️ How to Run

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
