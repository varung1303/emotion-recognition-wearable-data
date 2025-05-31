# 😄 Emotion Recognition Using Wearable Sensor Data

This project explores the use of physiological signals collected from wearable devices to recognize emotional states such as **stress**, **amusement**, **meditation**, and **baseline**. Leveraging both classical machine learning and deep learning models, this study aims to build a reliable emotion classification system using real-world biosignals.

---

## 📌 Project Overview

### 🧩 Problem Statement

Can we detect human emotions in real time using non-invasive wearable sensors?

### 🎯 Objective

To develop predictive models that classify emotional states based on data collected from wearable devices, enabling real-time mental health insights, personalized wellness, and improved human-computer interaction.

---

## 📊 Dataset: WESAD

- **Source**: [WESAD dataset](https://archive.ics.uci.edu/ml/datasets/WESAD)
- **Modality**: Multimodal signals collected from wrist and chest sensors
- **Signals**:
  - Chest: EDA, EMG, ECG, Respiration, Temperature
  - Wrist: EDA, BVP, Temperature
- **Emotion Labels**: `Baseline`, `Stress`, `Amusement`, `Meditation`

---

## 🔧 Methodology

### 📐 Preprocessing
- Imputation of missing values
- Z-score normalization
- Label encoding
- Time window segmentation

### 🔍 Feature Engineering
- Statistical features (mean, std, min, max)
- Frequency-domain features for HRV
- Correlation analysis for feature selection

### 🤖 Models Implemented
| Model                    | Accuracy |
|--------------------------|----------|
| Random Forest            | 99.5%    |
| Gradient Boosting        | 98.5%    |
| MLP Neural Network       | 96%      |
| LSTM (Deep Learning)     | 84%      |
| SVM                      | 83%      |
| Logistic Regression      | 52%      |

## 🧰 Tech Stack

- **Languages**: Python
- **Libraries**: scikit-learn, NumPy, pandas, matplotlib, seaborn, Keras, PyTorch
- **Notebook**: Jupyter
- **Dataset**: CSV-formatted time series from WESAD

## 🚀 Future Work

- Integrate attention-based models (Transformers)
- Deploy a real-time edge-based version on mobile
- Collect and test on diverse population data
- Sensor fusion with EEG for better context

---

## ⚖️ Ethical Considerations

- Privacy of physiological and emotional data
- Fairness and bias across demographic groups
- Informed consent and transparent use cases

---


