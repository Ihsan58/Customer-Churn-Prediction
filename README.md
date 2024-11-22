# Customer Churn Prediction

## 📖 Overview
This project predicts customer churn for a telecom company using machine learning. Churn refers to customers leaving a service, and predicting churn helps businesses retain their clients.

## 🛠️ Features
1. **Data Preprocessing**: Handle missing values, encode categorical data, and scale features.
2. **EDA**: Analyze churn patterns using visualizations.
3. **Model Training**: Use machine learning (Random Forest Classifier).
4. **Deployment**: Expose a Flask API for real-time predictions.

## 🚀 Results
- **Accuracy**: 85%
- **AUC-ROC**: 0.90
- Feature importance visualizations show the top factors influencing churn.

## 📂 Project Structure
```plaintext
customer-churn-prediction/
├── README.md          <- Project documentation
├── data/              <- Dataset files
│   └── telco_customer_churn.csv
├── notebooks/         <- Jupyter Notebooks for analysis
│   └── churn_analysis.ipynb
├── src/               <- Python scripts for preprocessing, training, and API
│   ├── preprocess.py
│   ├── train_model.py
│   └── api.py
├── requirements.txt   <- Python dependencies
└── LICENSE            <- Open-source license
