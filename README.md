# generativeai_project
# 📊 Multi-Class Emotion Detection from Tweets using Deep Learning (LSTM Model)

## 📌 Overview

This project aims to classify emotions in tweets into one of six categories: `joy`, `anger`, `sadness`, `fear`, `love`, and `surprise`. A Long Short-Term Memory (LSTM) model is utilized for its strength in capturing sequential dependencies within text data.

---

## 🚀 Features
- Deep Learning-based emotion classification.
- Text preprocessing: tokenization, padding, label encoding.
- Achieves high accuracy on Hugging Face Emotion Dataset.
- Includes performance analysis using accuracy, F1-score, and confusion matrix.
- Discusses class imbalance challenges and future enhancements.

---

## 🛠️ Technologies Used
- Python
- TensorFlow / Keras
- Pandas, NumPy
- Scikit-learn
- Hugging Face Datasets

---

## 🏗️ Model Architecture
- **Embedding Layer**: Converts words into dense vectors (embedding dim: 100)
- **SpatialDropout1D**: Dropout rate: 0.2
- **LSTM Layer**: 100 units, dropout: 0.2, recurrent dropout: 0.2
- **Dense Layer**: 6 units (one per emotion) with softmax activation

---

## 📊 Evaluation Metrics
- **Accuracy**
- **Weighted F1-score**
- **Confusion Matrix**

---

## 📈 Results

| Metric              | Value   |
|:------------------|:---------|
| **Test Accuracy**   | 92.5%    |
| **Weighted F1-score** | 0.92  |

- Strong performance for most classes.
- Lower performance for underrepresented classes: `Anger` and `Surprise`.

---

## 📚 Dataset
- **Name**: Hugging Face Emotion Dataset
- **Description**: A collection of tweets labeled with six emotion categories.
- **Preprocessing**:
  - Tokenization
  - Padding (max sequence length: 100)
  - Label Encoding (one-hot vectors)

## 👤 Contribution

**Busra Agbaba**  
- Implemented and trained the LSTM model.
- Handled text preprocessing and data preparation.
- Conducted evaluation and performance analysis.
- Documented results and proposed future improvements.
