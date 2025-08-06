# 🤖 Deepfake Detection on Social Media using LSTM + NLP

## 📌 Project Overview

This project detects **AI-generated tweets** (deepfake text) using Natural Language Processing (NLP) and deep learning.

We used **FastText embeddings** combined with **LSTM networks** to classify machine-generated vs human-written tweets with ~92% accuracy.

---

## 💡 Key Features

- Preprocessed tweet data with tokenization and padding
- Used FastText for dense word embeddings
- Trained a Bidirectional LSTM for sequence classification
- Evaluated with accuracy, confusion matrix, and ROC curve

---

## 📊 Results

- ✅ Accuracy: ~92%
- 📈 Precision, Recall, F1-score: High across both classes
- 🔍 Model correctly identifies GPT/BERT-generated tweets

---

## 🧰 Tech Stack

- Python (Pandas, NumPy, Keras, TensorFlow)
- FastText word embeddings
- LSTM & BiLSTM layers
- Jupyter Notebook
- GitHub for versioning

---

## 📁 Project Structure

```bash
deepfake-tweet-detector/
├── deepfake_detector.ipynb
├── dataset/tweets_dataset.csv
├── models/lstm_model.h5
├── visuals/confusion_matrix.png
└── README.md

