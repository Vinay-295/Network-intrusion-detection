🔐 Quantum Machine Learning for Network Intrusion Detection

A Hybrid Quantum-Classical Machine Learning approach for detecting and classifying network attacks using the CICIDS2017 dataset.

📌 Overview

This project explores the application of Quantum Machine Learning (QML) for Network Intrusion Detection. Classical preprocessing techniques are combined with Quantum ML and classical ML models to classify benign and malicious network traffic.

📊 Dataset

CICIDS2017 — Canadian Institute for Cybersecurity Intrusion Detection System Dataset 2017.

The dataset contains realistic benign and malicious network traffic with flow-based network features.

A processed sample, CICIDS2017_700.csv, is used for experimentation.

⚙️ Methodology

CICIDS2017
    ↓
Data Preprocessing
    ↓
Feature Scaling
    ↓
Feature Selection
    ↓
PCA
    ↓
Classical ML + Quantum ML
    ↓
Model Evaluation & Comparison

🤖 Models

Classical ML

Logistic Regression
Random Forest
SVM
XGBoost
KNN

Quantum ML

QSVM
VQC
QNN
🛠️ Technologies
Python
Pandas & NumPy
Scikit-learn
XGBoost
Qiskit
Qiskit Machine Learning
Matplotlib & Seaborn
Google Colab
📈 Evaluation

Models are compared using:

Accuracy
Precision
Recall
F1-Score
Confusion Matrix
ROC/AUC
Cross-Validation

🚀 Future Work

Experiment with the complete CICIDS2017 dataset
Test models on real quantum hardware
Improve class imbalance handling
Explore advanced hybrid quantum-classical architectures
