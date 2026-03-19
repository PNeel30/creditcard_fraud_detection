# 💳 Credit Card Fraud Detection App

This is a Streamlit-based web application that detects fraudulent credit card transactions using a Logistic Regression model. Users can either upload a batch of transaction data or enter details manually to get instant predictions.

---

## 🚀 Features

- ✅ *Batch Prediction* via CSV upload
- ✍ *Manual Input* of transaction data
- 📊 *Prediction summary* with counts and visualizations
- 🧁 *Interactive pie chart* of transaction types (Fraud/Normal)
- 💰 *Total amount analysis* per transaction type
- 📥 *Downloadable prediction results*

---

## 📁 Dataset

The app uses the [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) which contains:

- *284,807 transactions* from two days in September 2013
- Features V1 to V28 (PCA-transformed)
- Time, Amount, and Class columns
- Class = 1 → Fraudulent | Class = 0 → Normal
