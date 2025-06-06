# 🐦 Twitter Sentiment Analysis using NLP

This project analyzes Twitter data to understand public sentiment toward specific topics, products, or events using **Natural Language Processing (NLP)** techniques. Implemented in **Google Colab**, the model processes tweet text, extracts sentiment, and classifies it as positive or negative.

---


## 📌 Features

- User-defined topic analysis (e.g., "iPhone", "Elections")
- Tweet preprocessing with:
  - Text cleaning (regex)
  - Stopword removal
  - Stemming using PorterStemmer
- Sentiment classification using:
  - TF-IDF Vectorizer
  - Logistic Regression
- Accuracy metrics for training and testing
- Option to test predictions on unseen tweets
- Save & load trained model using Pickle

---

## 📂 Dataset

- [Sentiment140](https://www.kaggle.com/datasets/kazanova/sentiment140)
- CSV file with 1.6 million labeled tweets
- Columns used:
  - `target`: Sentiment label (0 = negative, 4 = positive)
  - `text`: Raw tweet content

---

## 📊 How It Works

1. Load and preview dataset
2. Ask user for a **topic to analyze** (e.g., `iPhone`)
3. Filter tweets by that topic
4. Preprocess the text
5. Train/Test split (80/20)
6. Transform text using TF-IDF
7. Train Logistic Regression model
8. Predict sentiment & calculate accuracy
9. Save the model with Pickle
10. Predict sentiment on new test tweets

---

## 🛠️ Technologies Used

- Python (Google Colab)
- Pandas & NumPy
- NLTK
- Scikit-learn
- Pickle
- Matplotlib/Seaborn (for optional visualizations)
