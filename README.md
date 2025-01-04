# Credit Card Default Prediction

This project focuses on using machine learning techniques to predict credit card defaults using the Kaggle "American Express - Default Prediction" dataset. The goal is to evaluate the performance of various machine learning algorithms, including **XGBoost**, **Neural Networks**, **Ensemble Methods**, **Random Forest Classifier (RFC)**, **Decision Tree Classifier (DTC)**, and **Logistic Regression Classifier (LRC)**, in predicting whether a customer will default on their credit card.
 
## Objectives

- Evaluate and compare the performance of various machine learning algorithms in predicting credit card defaults.
- Use **Ensemble Learning (Stacking)** to improve prediction accuracy.

## Algorithms Tested

- **XGBoost (XGB)**
- **Neural Network (NN)**
- **Ensemble Methods**
- **Random Forest Classifier (RFC)**
- **Decision Tree Classifier (DTC)**
- **Logistic Regression Classifier (LRC)**

## Methods

1. **Data Collection & Preprocessing:** The Kaggle dataset is cleaned and preprocessed to ensure the data is ready for modeling.
2. **Feature Engineering:** We extracted relevant features for predicting credit card defaults.
3. **Addressing Class Imbalance:** Applied **SMOTE** to balance the dataset by generating synthetic data points for the underrepresented class.
4. **Model Evaluation:** Models were evaluated using various metrics such as **Accuracy**, **Precision**, **Recall**, **F1-Score**, **AUC**, and **Gini Index** to identify the best model for credit card default prediction.

## Results

- The **XGBoost** and **Ensemble Models** performed the best with an **AUC of 0.96** and a **Gini index of 0.92**.
- The **Random Forest** model followed closely behind with an **AUC of 0.95** and a **Gini index of 0.90**.
- **Neural Networks** showed the highest **Recall**, which is crucial for identifying defaults.
