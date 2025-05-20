# Aware of Your Stress: A Stress Detection Using Wearable Watch

This project focuses on predicting stress levels using physiological data collected from a wearable watch. The goal is to assess the predictive accuracy of machine learning models and evaluate whether the device is suitable for stress detection in patients.

## Project Overview

- **Dataset:** The raw data of participants ID11 to ID35 (25 participants). The data and the detailed descriptions can be found at the following link: https://github.com/italha-d/Stress-Predict-Dataset.git, and the processed data is in 'StressDetection.csv' file. The features in this project include heart rate (HR), blood volume pressure (BVP), accelerometer (ACC), skin conductance (EDA), inter-beat interval (IBI), and skin temperature (TEMP).
- **Goal:** Build machine learning models that predict stress vs non-stress states.
- **Motivation:** Early and accurate stress detection can help patients manage their mental health.

## Methods and Tools
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Machine Learning Models (Random Forest, Support Vector Machine, K-Nearest Neighbors, Ridge Logistic Regression)
- Data Preprocessing (Interpolation, Normalization)
- Evaluation Metrics (Accuracy, F1-Score, False Negative Rate)

## Steps

**1. Data Cleaning and Preprocessing:**
- Handle missing values.
- Encode categorical variables.
- Normalize numerical features.

**2. Feature Selection:**
- Select relevant physiological features for prediction.

**3. Model Training:**
- Train multiple machine learning models.
- Perform train-test split to validate models.

**4. Model Evaluation:**
- Compare model performance using accuracy and confusion matrices.
- Analyze classification reports to identify best-performing model.

## Results

- Random Forest model achieved the highest classification accuracy among tested models.
- Key indicators for stress detection included heart rate variability and skin conductance.
