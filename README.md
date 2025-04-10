# 🛡️ Anomaly Detection in Cybersecurity Using AI and ML

This project aims to detect cybersecurity anomalies using a hybrid approach that combines Machine Learning (ML) and Deep Learning (AI) models. The study focuses on the UNSW-NB15 dataset, a comprehensive and publicly available dataset that contains modern synthetic attack traffic and benign network behaviors.


## 📌 Project Overview

- **Objective:** To detect anomalies and cyberattacks using ML models (Random Forest, SVM, XGBoost) for feature selection/classification and AI models (LSTM, CNN, Autoencoder) for deep anomaly detection.
- **Approach:** 
  - Initial analysis on one CSV file.
  - For scalability and performance improvement, all four dataset files were merged and used.
  - A hybrid model approach was implemented to enhance detection accuracy and outperform traditional standalone models.

## 🧠 Models Implemented

### 🔷 Machine Learning
- Random Forest (RF)
- Support Vector Machine (SVM)
- XGBoost

### 🔷 Deep Learning (AI)
- Long Short-Term Memory (LSTM)
- Convolutional Neural Network (CNN)
- Autoencoder

## 📊 Tools & Technologies

- **Python** (pandas, scikit-learn, TensorFlow, Keras, matplotlib, seaborn, numpy)
- **Jupyter Notebook / Google Colab / VS Code**
- **Visualization:** Power BI, Tableau
- **SMOTE** for handling class imbalance
- **EarlyStopping**, **TensorBoard** for training monitoring

## 📁 Dataset

- **Name:** [UNSW-NB15 Dataset](https://research.unsw.edu.au/projects/unsw-nb15-dataset)
- **Source:** Australian Centre for Cyber Security (ACCS)
- **Format:** 4 CSV files (merged for final analysis)
- **Features:** 49 total features + label
- **Attack Categories:** Includes DoS, Fuzzers, Reconnaissance, Shellcode, Backdoor, etc.

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/anomaly-detection-cybersecurity.git
   cd anomaly-detection-cybersecurity
