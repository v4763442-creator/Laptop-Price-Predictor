# 💻 Laptop Price Predictor

A Machine Learning web application that predicts the approximate price of a laptop based on its specifications.

The model is trained on laptop specification data and deployed using Streamlit Community Cloud.

## 🚀 Live Demo

👉 [Laptop Price Predictor](YOUR_STREAMLIT_URL)

## 📌 Project Overview

Buying a laptop can be difficult because prices depend on multiple specifications such as brand, RAM, processor, storage, display features, GPU and operating system.

This project uses Machine Learning to estimate the price of a laptop based on its specifications.

The complete project covers:

- Data preprocessing
- Exploratory Data Analysis
- Feature engineering
- Categorical encoding
- Model training
- Model evaluation
- Pipeline creation
- Streamlit deployment

## ✨ Features

- Select laptop brand
- Select laptop type
- Select RAM
- Enter laptop weight
- Select touchscreen availability
- Select IPS display
- Enter screen size
- Select CPU
- Select GPU
- Select operating system
- Specify storage configuration
- Get an estimated laptop price

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Matplotlib
- Seaborn
- Pickle

## 🤖 Machine Learning

The project uses a Scikit-learn preprocessing and machine learning pipeline.

Categorical features are transformed using OneHotEncoder and numerical features are processed before being passed to the regression model.

The trained pipeline is saved as:

```text
pipe.pkl
