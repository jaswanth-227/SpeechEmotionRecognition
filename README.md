# 🎙️ Speech Emotion Recognition using Machine Learning

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Poppins&size=28&duration=3500&pause=1000&color=FF6B6B&center=true&vCenter=true&width=900&lines=Speech+Emotion+Recognition;Machine+Learning+on+RAVDESS+Dataset;Emotion+Classification+using+Audio+Features;Random+Forest+%7C+SVM+%7C+XGBoost" />
</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?style=for-the-badge&logo=scikitlearn)
![XGBoost](https://img.shields.io/badge/XGBoost-Gradient%20Boosting-red?style=for-the-badge)
![Librosa](https://img.shields.io/badge/Librosa-Audio%20Processing-success?style=for-the-badge)
![Dataset](https://img.shields.io/badge/Dataset-RAVDESS-blueviolet?style=for-the-badge)

</p>

---

# 📖 Overview

Speech Emotion Recognition (SER) is a key application of Artificial Intelligence that enables machines to identify human emotions from speech signals.

This project develops a machine learning pipeline for recognizing emotions from audio recordings using the **RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)** dataset. The workflow includes feature extraction from speech signals, training multiple classifiers, and evaluating their performance on both validation and external datasets to assess generalization.

---

# 🎯 Objectives

- Build a robust Speech Emotion Recognition (SER) system.
- Extract informative acoustic features from speech signals.
- Compare multiple machine learning algorithms.
- Evaluate model performance using standard classification metrics.
- Analyze model generalization on unseen real-world audio.

---

# 🎭 Recognized Emotions

The system classifies the following eight emotions:

- 😐 Neutral
- 😌 Calm
- 😀 Happy
- 😢 Sad
- 😠 Angry
- 😨 Fearful
- 🤢 Disgust
- 😲 Surprised

---

# 📂 Dataset

**Dataset:** RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)

📂 **Download Dataset**

https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio

### Dataset Statistics

| Property | Value |
|----------|-------|
| Actors | 24 |
| Male | 12 |
| Female | 12 |
| Emotions | 8 |
| Audio Format | WAV |
| Sampling Rate | 48 kHz |

---

# ⚙️ Methodology

```text
Speech Audio
      │
      ▼
Audio Preprocessing
      │
      ▼
Feature Extraction
(MFCC, Chroma, Spectral Features)
      │
      ▼
Feature Vector
      │
      ▼
Machine Learning Models
      │
      ▼
Emotion Prediction
```

---

# 🎵 Feature Extraction

Audio features were extracted using the **Librosa** library.

| Feature | Description |
|----------|-------------|
| MFCC | Captures speech timbre characteristics |
| Chroma | Represents pitch information |
| Spectral Contrast | Measures spectral peaks and valleys |
| Zero Crossing Rate | Indicates signal sign changes |
| Root Mean Square (RMS) | Represents signal energy |

These features were concatenated to create a numerical representation for each speech sample.

---

# 🤖 Machine Learning Models

The following classifiers were trained and compared:

| Model | Purpose |
|--------|----------|
| 🌳 Random Forest | Ensemble Classification |
| 📈 Support Vector Machine (SVM) | Maximum Margin Classification |
| ⚡ XGBoost | Gradient Boosting |

---

# 📊 Model Evaluation

Performance was evaluated using:

- ✅ Accuracy
- ✅ Precision
- ✅ Recall
- ✅ F1-Score
- ✅ Confusion Matrix
- ✅ Classification Report
- ✅ Cross-Validation Score

---

# 🧪 Generalization Study

To evaluate robustness beyond the training dataset, the trained models were tested on external speech recordings.

### Key Observations

- Validation accuracy was significantly higher than external test accuracy.
- Speaker variations and recording conditions affected performance.
- Background noise and accent differences introduced prediction challenges.

This highlights the importance of improving model generalization for real-world deployment.

---

# 📈 Challenges

- Difficulty distinguishing acoustically similar emotions.
- Limited generalization to unseen speakers.
- Variability in recording quality.
- Background noise affecting predictions.

---

# 🚀 Future Improvements

- 🧠 Convolutional Neural Networks (CNNs)
- 🔁 Long Short-Term Memory Networks (LSTMs)
- 🎵 Spectrogram-based Deep Learning
- 🤖 Transformer-based Audio Models
- 🎤 Data Augmentation
- 🌍 Real-Time Speech Emotion Recognition

---

# 🛠️ Technology Stack

### Programming Language

- Python

### Libraries

- Librosa
- NumPy
- Pandas
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn

---

# 📂 Repository Structure

```text
Speech-Emotion-Recognition
│
├── dataset/
├── notebooks/
├── models/
├── audio_samples/
├── results/
├── requirements.txt
├── speech_emotion_recognition.ipynb
└── README.md
```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Speech-Emotion-Recognition.git

cd Speech-Emotion-Recognition
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Usage

Run the notebook

```bash
jupyter notebook
```

or execute

```bash
python emotion_recognition.py
```

---

# 📊 Future Extensions

- Real-time microphone emotion detection
- Emotion recognition from multilingual speech
- Audio-visual emotion recognition
- Mobile deployment
- Cloud API using FastAPI

---


**Jaswanth Yadurla**

🎓 B.Tech – Artificial Intelligence & Machine Learning

📧 **yadurlajaswanth@gmail.com**

🔗 **LinkedIn:** https://www.linkedin.com/in/jaswanth-yadurla-634290284/

---

# 🙏 Acknowledgements

- **RAVDESS Dataset** – Livingstone & Russo (2018)
- Kaggle Community
- Librosa Development Team
- Scikit-learn Contributors

---

<p align="center">

⭐ **If you found this project useful, please consider giving it a Star!**

Made with ❤️ by **Jaswanth Yadurla**

</p>
