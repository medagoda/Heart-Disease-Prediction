Heart Attack Analysis & Prediction
This project is part of the DataTalks.Club ML Zoomcamp midterm. It is a classification model that predicts whether a person is at risk of a heart attack based on clinical parameters. The model is deployed using Streamlit.

<p align="center"> <img src="https://cdn.dribbble.com/users/2154580/screenshots/6452241/atemlos_loop_heart_v1.0_chriseff_dribbble.gif" width="500" height="400" /> </p>
🔗 Links
Dataset: Kaggle Dataset

Notebook: Kaggle Code

Live App: Streamlit App

📌 Overview
Heart disease is a major cause of death worldwide. Predicting the chances of a heart attack early can help save lives. This project uses machine learning to make that prediction using patient data.

🧪 Steps in the Project
Data Preprocessing

Exploratory Data Analysis (EDA)

Feature Engineering

Scaling and Normalization

Model Training and Evaluation

Model Testing

Deployment with Streamlit

🧾 Input Features
age: Age of the person

sex: 1 = Male, 0 = Female

cp: Chest pain type (0–3)

trestbps: Resting blood pressure

chol: Cholesterol level

fbs: Fasting blood sugar (>120 mg/dl)

restecg: ECG results (0–2)

thalach: Max heart rate achieved

exang: Exercise-induced angina (1 = Yes, 0 = No)

oldpeak: ST depression

slope: Slope of the ST segment (0–2)

ca: Number of major vessels (0–3)

thal: Thalassemia type (1–3)

target: 1 = Risk, 0 = No risk

✅ Model Details
Models used:

Decision Tree

Random Forest

XGBoost (Best accuracy and AUC)

Visualization tools:

Matplotlib

Seaborn (Heatmaps)

Deployed using:

Streamlit Cloud

<p align="center"> <img src="predict heart attack.gif" /> </p>
🔄 Future Improvements
Add cross-validation

Use pipelines for better training flow

Try other feature selection methods

Handle outliers with Z-scores

Explore more classification models

Add more detailed EDA
