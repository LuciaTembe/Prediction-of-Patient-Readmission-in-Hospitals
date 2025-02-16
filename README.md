# Prediction-of-Patient-Readmission-in-Hospitals
This project uses machine learning and deep learning techniques to predict patient readmission within hospitals. The research was conducted to improve hospital management and patient care by identifying high-risk readmissions

# Overview
The project focuses on predicting 30-day hospital readmission for diabetic patients, using machine learning and deep learning models. The study highlights the importance of hospital readmission rates as a metric for evaluating patient care effectiveness.

# Dataset
The dataset used is Diabetes 130-US (1999-2008), which includes 101,766 patient records with attributes like demographics, lab tests, diagnoses, medications, and readmission status.

# Models Used
Machine Learning: XGBoost, Random Forest.
Deep Learning: Neural Networks (NN), Multi-Layer Perceptron (MLP), Convolutional Neural Network (CNN), and Long Short-Term Memory (LSTM).

# Feature Engineering
The study includes one-hot encoding, label encoding, and PCA/Boruta for feature selection.

# Data Handling
The study applies SMOTE (oversampling) and undersampling techniques to address class imbalance, as only 11.2% of cases were labeled as readmitted.

# Performance
MLP (One-Hot Encoding) performed best with 89% accuracy.
LSTM & NN (Label Encoding) achieved 88% accuracy.
