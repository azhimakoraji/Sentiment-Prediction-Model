
# 💬 Sentiment Prediction Model

A sentiment classification model that predicts whether a sentence expresses a **positive** or **negative** sentiment using a neural network.

---

## 🧠 Overview

This project uses deep learning (TensorFlow) to classify sentiment from text input. It is trained on a labeled dataset with emotional and sentiment tags from Kaggle.

- **Dataset:** [Kaggle Sentiment and Emotion Analysis Dataset](https://www.kaggle.com/datasets/kushagra3204/sentiment-and-emotion-analysis-dataset)
- **Size:** ~3,304 sentences, ~45,000 words
- **Context:** Sentences related to cinema experiences, containing both emotional and contextual keywords (e.g., *good, great, movie, food, time*)

---

## 🧹 Preprocessing Steps

- Removed punctuation and numbers
- Lowercased all words
- Removed stopwords
- Lemmatized words
- Explored three vectorization options: Bag of Words, TF-IDF, and Word2Vec
- Data split using **stratified sampling**

---

## 🧪 Modeling Approach

- Framework: **TensorFlow**
- Input vectorization: **Bag of Words** (selected due to highest AUC performance)
- Target class: **Balanced**, thus evaluation metric of choice: **ROC-AUC**
- Best model achieved **AUC-ROC = 0.8759**

---

## 📈 Results

The model performed well in distinguishing true positives and true negatives. The final model was selected based on AUC performance, and demonstrates practical use for simple sentence-level sentiment classification.

---

## 📁 File Structure

```
.
├── Sentiment Analysis I.ipynb      # Jupyter notebook with EDA, modeling & evaluation
├── MODEL PREDIKTOR SENTIMENT.pptx  # Project presentation with model overview
├── README.md                       # Project description
```

---

## 📸 Demo

Refer to `MODEL PREDIKTOR SENTIMENT.pptx` for visuals and a summary of model design and results.

---

## 🙋‍♂️ Author

**Azhima Koraji**  
