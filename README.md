# 🎯 Machine Learning Project - Emotion Recognition Using RAVDESS Dataset

## 📌 Project Overview

This project explores **Speech Emotion Recognition (SER)** using the **RAVDESS dataset**. The aim is to classify human emotions from audio recordings with machine learning techniques. 

The project includes:
- Preprocessing raw audio into numerical features
- Training multiple ML models (Random Forest, SVM, XGBoost)
- Evaluating performance on validation and external test data
- Analyzing generalization challenges

---

## 📂 Dataset Description

**Dataset:** [RAVDESS - Ryerson Audio-Visual Database of Emotional Speech and Song](https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio)

- 🎙️ 24 professional actors (12 male, 12 female)
- 8 emotions: **neutral, calm, happy, sad, angry, fearful, disgust, surprised**
- Audio samples provided in high-quality 48kHz WAV format

---

## 🔧 Features Extracted

Using `librosa`, the following features are extracted from each audio file:
- **MFCCs (Mel-Frequency Cepstral Coefficients)**
- **Chroma Features**
- **Spectral Contrast**
- **Zero-Crossing Rate**
- **Root Mean Square Energy**

These features are then aggregated to form the input for the classifiers.

---

## 🤖 Models Used

The following machine learning models were trained and evaluated:
- **Random Forest Classifier**
- **Support Vector Machine (SVM)**
- **XGBoost Classifier**

Models are evaluated using metrics such as:
- **Accuracy**
- **Classification Report**
- **Confusion Matrix**
- **Cross-Validation Scores**
---

## 🧪 Generalization Test

To test model robustness, the trained models were also evaluated on **external audio files**. Key observations include:
- A notable gap between validation accuracy and real-world performance
- Differences due to variations in speaker accents, background noise, and other external factors

---

## 🚧 Challenges & Next Steps

### ❗ Challenges Faced:
- Generalization gap on external data
- Difficulty in differentiating closely related emotions (e.g., **sad** vs. **calm**)

### 📈 Improvements Planned:
- **Deep Learning:** Explore Convolutional Neural Networks (CNNs) and Long Short-Term Memory networks (LSTMs) on spectrogram data.
- **Transfer Learning:** Use pre-trained audio models to boost performance.

---

## 💻 Tools & Libraries Used

- Python 🐍
- `librosa`, `numpy`, `pandas`
- `scikit-learn`, `xgboost`
- `matplotlib`, `seaborn`

---

## 🙌 Acknowledgements

- **Dataset:** © 2018 Livingstone & Russo (RAVDESS)
- Thanks to the Kaggle community for their insightful notebooks and discussions

---
