# Fraud_Detection-Prediction

This project is a machine learning-based approach to detect fraudulent credit card transactions using logistic regression. The model is trained on real-world data from Kaggle and deployed through a Streamlit web app for easy interaction and prediction.

---

## Dataset

- **Source:** [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- The dataset contains transactions made by European cardholders in September 2013.
- Features are anonymized (`V1`–`V28`) due to confidentiality, along with `Time`, `Amount`, and the target variable `Class`:
  - `Class = 0`: Legitimate transaction
  - `Class = 1`: Fraudulent transaction

---

##  Machine Learning Model

- **Algorithm:** Logistic Regression
- **Preprocessing:**
  - **StandardScaler** to scale numerical features
  - **OneHotEncoder** to encode categorical variables
  - **ColumnTransformer** to combine transformations

- **Pipeline:** Implemented using Scikit-learn's `Pipeline` and `ColumnTransformer`
- **Evaluation Metrics:**
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - ROC AUC

---

##  Streamlit Web App

A simple and interactive web interface allows users to input transaction features and get real-time fraud predictions.


