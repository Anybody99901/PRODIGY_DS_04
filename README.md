
### 🧠 Prodigy Infotech Internship - Task 4

## 🎯 Project: Sentiment Analysis on Twitter Data

This project analyzes and visualizes **sentiment patterns in social media data** to understand public opinion and attitudes toward specific topics or brands.
We used a labeled dataset of tweets with entities and sentiment tags to perform **Natural Language Processing (NLP)** and generate visual insights.

---

## 📁 Dataset

We used:

* `twitter_training.csv`
* `twitter_validation.csv`

Each file contains:

* `Tweet Id` — Unique ID
* `Entity` — Brand or topic referenced
* `Sentiment` — Labeled as Positive, Negative, or Neutral
* `Tweet` — The actual tweet text

📌 Dataset Source: [Kaggle - Twitter Entity Sentiment Analysis](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis)

---

## ⚙️ Tools and Libraries

* Python
* Google Colab
* `pandas`, `seaborn`, `matplotlib`
* `nltk`, `wordcloud`, `scikit-learn`

---

## 🔍 Steps Implemented

1. **Load and inspect** the dataset
2. **Clean and preprocess** tweet text (remove URLs, mentions, stopwords, etc.)
3. **Visualize** overall sentiment distribution
4. **Generate word clouds** for each sentiment class
5. **Analyze entity-level sentiment** patterns using grouped plots and heatmaps
6. *(Optional)*: Apply TF-IDF vectorization for future classification or modeling tasks

---

## 📊 Visual Results

| Sentiment Distribution                   | Word Clouds                  |
| ---------------------------------------- | ---------------------------- |
| ![Sentiment]![Image](https://github.com/user-attachments/assets/933bd298-9bea-4ed7-93f0-338787ab0221) | ![WordCloud](wordclouds.png) |


## 🚀 Run This Project

### 🧪 Option 1: Run on Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/prodigy-task-4-sentiment-analysis/blob/main/sentiment_analysis.ipynb)

### 🧰 Option 2: Run Locally

```bash
pip install pandas matplotlib seaborn nltk wordcloud scikit-learn
```

Then open the notebook and run all cells after uploading the dataset files.

---

## 📈 Outcome

* Cleaned and analyzed real-world tweet data
* Extracted public sentiment patterns about brands
* Gained hands-on experience in text processing and visualization
