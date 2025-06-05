# Customer Churn Prediction

A binary classification model built using TensorFlow/Keras to predict whether a customer is likely to churn based on their service usage and account information.

## Dataset

- **Source**: [Kaggle - Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **File Name**: `WA_Fn-UseC_-Telco-Customer-Churn.csv`
- **Target Column**: `Churn` (Yes/No)

## Model Summary

- Input features: 26 (after preprocessing)
- Architecture:
  - Dense(20, activation='relu')
  - Dense(1, activation='sigmoid')
- Loss function: `binary_crossentropy`
- Optimizer: `adam`
- Metric: `accuracy`

##  How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/customer_churn_prediction.git
   cd customer_churn_prediction
