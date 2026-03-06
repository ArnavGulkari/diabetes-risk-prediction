# Diabetes Risk Prediction

![Python](https://img.shields.io/badge/Python-3.10-blue) ![License](https://img.shields.io/badge/License-MIT-green) ![Status](https://img.shields.io/badge/Status-Completed-success)

## Project Overview
This project predicts the **risk of diabetes** in individuals using **XGBoost**, with a web deployment using **Flask**. The model is trained on structured health data and provides real-time predictions.

---

## Features
- Predict diabetes risk from user health data  
- Real-time predictions via a Flask web application  
- Data preprocessing, model training, and evaluation included  
- High accuracy with visualizations of model performance

---

## Dataset
The project uses structured health data with features such as:  
- Age  
- BMI  
- Blood Pressure  
- Glucose Level  
- Family History of Diabetes  

Dataset files are included in the repository under `data/`.

---

## Folder Structure

```text
diabetes-risk-prediction/
│
├── data/                       # Dataset files
│   └── diabetes.csv
├── notebooks/                  # Jupyter notebook for training and evaluation
│   └── diabetes-risk-prediction.ipynb
├── model/                      # Saved trained models
│   └── xgboost_model.pkl
├── app.py                      # Flask application
├── requirements.txt            # Python dependencies
└── README.md                   # Project documentation
