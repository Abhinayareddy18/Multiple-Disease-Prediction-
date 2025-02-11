# Multiple Disease Prediction System

## Overview

The **Multiple Disease Prediction System** is a machine learning-based web application that predicts the likelihood of three diseases: **Diabetes, Heart Disease, and Parkinson's Disease**. It provides a simple interface where users can enter medical parameters and receive instant predictions.

## Technologies Used

- **Machine Learning:** Scikit-Learn (SVM, Logistic Regression)
- **Data Processing:** Pandas, NumPy
- **Model Deployment:** Streamlit
- **Model Storage:** Pickle

## Features

- **Diabetes Prediction:** Uses the PIMA Diabetes dataset to classify whether a person is diabetic or not.
- **Heart Disease Prediction:** Uses heart health metrics to determine if a person has heart disease.
- **Parkinson's Prediction:** Analyzes voice and movement features to predict Parkinson's disease.
- **Web Interface:** A simple, interactive UI built with Streamlit.

## Project Structure

```
/Multiple-Disease-Prediction-System
│── app.py                    # Streamlit app for UI
│── saved_models/              # Folder containing trained ML models
│── diabetes.ipynb             # Jupyter Notebook for Diabetes Prediction
│── heart.ipynb                # Jupyter Notebook for Heart Disease Prediction
│── parkinsons.ipynb           # Jupyter Notebook for Parkinson's Prediction
│── requirements.txt           # Required Python packages
│── README.md                  # Project Documentation
```

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Multiple-Disease-Prediction.git
   cd Multiple-Disease-Prediction
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   streamlit run app.py
   ```

## Model Details

### 1. Diabetes Prediction

- **Dataset:** PIMA Diabetes Dataset
- **Model:** Support Vector Machine (SVM)
- **Metrics:** Accuracy score calculated for training and test data
- **Prediction Output:** 0 (Non-Diabetic) / 1 (Diabetic)

### 2. Heart Disease Prediction

- **Dataset:** UCI Heart Disease Dataset
- **Model:** Logistic Regression
- **Metrics:** Accuracy score computed for training and test data
- **Prediction Output:** 0 (No Heart Disease) / 1 (Heart Disease)

### 3. Parkinson's Disease Prediction

- **Dataset:** Parkinson's Disease Dataset
- **Model:** Support Vector Machine (SVM)
- **Metrics:** Accuracy score evaluated for training and test data
- **Prediction Output:** 0 (Healthy) / 1 (Parkinson's Disease)

## How It Works

1. Select the disease prediction type from the sidebar.
2. Enter the required health parameters.
3. Click the **Predict** button.
4. The system will provide an instant prediction based on the trained model.

## Future Enhancements

- Improve model accuracy with hyperparameter tuning.
- Add more disease predictions.
- Implement cloud-based deployment.

##

##
