# Restaurant Reviews – Sentiment Analysis (NLP Case Study)

This project performs sentiment analysis on restaurant reviews using Natural Language Processing (NLP) and machine learning. The goal is to classify whether a review is **positive (Liked = 1)** or **negative (Liked = 0)**.

---

## 🧠 Project Workflow

1. **Importing Data & Libraries**
2. **Text Preprocessing (NLTK):**
   - Lowercasing
   - Removing punctuation
   - Removing stopwords
   - Stemming (Porter Stemmer)
3. **Vectorization:**
   - Using `CountVectorizer`
4. **Model Building:**
   - Multinomial Naive Bayes Classifier
5. **Model Evaluation:**
   - Accuracy, Confusion Matrix, Classification Report
6. **Model Saving:**
   - Exported using `joblib`

---

## 📊 Dataset

- Source: [Kaggle – Restaurant Reviews (TSV)](https://www.kaggle.com/datasets/maher3id/restaurant-reviewstsv)
- Format: `.tsv` file
- Records: 1000 reviews
- Columns:
  - `Review` (text)
  - `Liked` (binary label)

---


