# 📰 Fake News Detection ML Project

A machine learning project to detect whether a news article is **Fake** or **Real** based on its content. This end-to-end project uses natural language processing techniques and supervised learning to build a binary classification model.

## 📌 Overview

Fake news has become a growing problem across social media and online platforms. This project trains a machine learning model using labeled datasets (`Fake.csv` and `True.csv`) to accurately classify news articles.

## 🛠️ Technologies Used

- **Python**
- **Pandas & NumPy** – Data handling and preprocessing
- **Scikit-learn** – ML models, TF-IDF vectorization, and evaluation
- **NLTK** – Text cleaning and stopword removal (optional)
- **Jupyter Notebook** – Development environment

## 📂 Dataset

- `Fake.csv`: Contains fake news articles
- `True.csv`: Contains true news articles
- Source: [Kaggle – Fake and Real News Dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)

## 🔍 ML Workflow

1. **Data Preprocessing**
   - Combine datasets and label them (0 = Fake, 1 = Real)
   - Clean text (remove punctuation, lowercase, etc.)
   - Train-test split (e.g., 80/20)

2. **Feature Extraction**
   - TF-IDF Vectorization of news content

3. **Model Training**
   - Trained using Logistic Regression (or any classifier like Naive Bayes, SVM)

4. **Model Evaluation**
   - Accuracy Score
   - Confusion Matrix
   - Classification Report

## 📈 Results

Achieved high accuracy in detecting fake vs. real news with proper evaluation metrics.


