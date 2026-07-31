# ❤️ Heart Stroke Prediction

An end-to-end Machine Learning project that predicts the likelihood of heart stroke based on patient health parameters. The project covers the complete ML workflow, from data preprocessing and model training to deployment using Streamlit.

## 📌 Project Overview

This project uses supervised machine learning algorithms to predict the risk of heart stroke using medical attributes. Multiple classification models were trained and evaluated to select the best-performing model for deployment.

## 🚀 Features

* Data preprocessing and cleaning
* Exploratory Data Analysis (EDA)
* Feature encoding and scaling
* Multiple ML model comparison
* Model evaluation using performance metrics
* Model serialization using Joblib
* Interactive Streamlit web application
* Real-time heart stroke prediction

## 📂 Dataset

The dataset includes patient health information such as:

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* Resting ECG
* Maximum Heart Rate
* Exercise-Induced Angina
* Oldpeak (ST Depression)
* ST Slope
* Heart Stroke Risk (Target)

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib
* Streamlit

## 🤖 Machine Learning Models

The following classification algorithms were implemented and compared:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* Decision Tree
* Gaussian Naive Bayes

Models were evaluated using:

* Accuracy Score
* F1 Score
* Classification Report
* Confusion Matrix

The best-performing model was saved using **Joblib** and integrated into the Streamlit application.

## 💻 Streamlit Application

The web application allows users to:

* Enter patient health details
* Predict heart stroke risk instantly
* View results through a simple and interactive interface

## ▶️ Run the Project

Clone the repository:

```bash
git clone https://github.com/your-username/Heart-Stroke-Prediction.git
```

Navigate to the project folder:

```bash
cd Heart-Stroke-Prediction
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Run the Streamlit application:

```bash
streamlit run app.py
```
## 🚀 Live Demo

**Application:**https://heart-stroke-prediction-44e2.onrender.com


⭐ Feel free to explore the project, provide feedback, or contribute!
