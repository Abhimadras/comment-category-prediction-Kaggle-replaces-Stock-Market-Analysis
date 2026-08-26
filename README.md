# 🏷️ Comment Category Prediction — Kaggle Challenge

Multi-class text classification model predicting comment categories via
engineered features and ensemble modeling — 81% accuracy on the held-out
leaderboard set.

![Python](https://img.shields.io/badge/Python-3.11-3776AB?logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?logo=scikitlearn&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-Competition-20BEFF?logo=kaggle&logoColor=white)
![NLP](https://img.shields.io/badge/NLP-Text%20Classification-8A2BE2)

## 📌 Overview

Solution to Kaggle's Comment Category Prediction Challenge — classifying
user comments into predefined categories. Focus was on feature engineering
over raw text (rather than jumping straight to deep learning) and combining
multiple models into an ensemble for a robust final score.

## 🎯 Key Result

| Metric | Result |
|---|---|
| Final accuracy | 81% |
| Approach | Feature engineering + ensemble modeling |
| Competition period | Jan–Mar 2026 |

## 🧠 What's Inside

- **Text Preprocessing** — cleaning, tokenization, and normalization of raw
  comment text.
- **Feature Engineering** — [fill in specifics: e.g. TF-IDF vectors, n-grams,
  comment length/punctuation/sentiment features, custom handcrafted
  signals — whatever you actually used].
- **Model Ensemble** — [fill in: e.g. combining Logistic Regression + Random
  Forest + Gradient Boosting via voting/stacking] to push past any single
  model's ceiling.
- **Validation** — cross-validation strategy used to avoid overfitting to
  the public leaderboard.

## 🛠️ Tech Stack

**Languages:** Python (pandas, NumPy, scikit-learn)
**NLP:** [fill in — e.g. TF-IDF / NLTK / spaCy]
**Modeling:** Ensemble methods (e.g. Voting/Stacking Classifier)

## 📂 Repo Structure

comment-category-prediction/ ├── notebooks/ │ └── comment_category_prediction.ipynb ├── data/ # Kaggle dataset (or link if size-restricted) ├── submission/ │ └── submission.csv └── README.md


## 🚀 Run Locally

```bash
git clone https://github.com/Abhimadras/comment-category-prediction.git
cd comment-category-prediction
pip install -r requirements.txt
jupyter notebook notebooks/comment_category_prediction.ipynb
```

## 👤 Author

**Abhijeet Gupta** — Data & Product Analyst
[[LinkedIn](#)](https://www.linkedin.com/in/abhijeetgupta22) · [[Portfolio](#)](https://abhimadras.github.io/Portfolio-/) · abhijeetgupta2802@gmail.com
