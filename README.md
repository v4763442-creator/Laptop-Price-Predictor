# 💻 Laptop Price Predictor

A Machine Learning web application that predicts the approximate price of a laptop based on its specifications.

The project follows an end-to-end Machine Learning workflow, including data cleaning, exploratory data analysis, feature engineering, preprocessing, model training, evaluation, and deployment using Streamlit.

## 🚀 Live Demo

### 👉 [Try the Laptop Price Predictor](https://laptop-price-predictor-7bdqkdfk4tmc2tbjcymima.streamlit.app/)

Enter the laptop specifications and get an estimated laptop price instantly.

---

## 📌 Project Overview

Laptop prices depend on various factors such as brand, processor, RAM, storage, GPU, display characteristics, operating system, and weight.

This project uses Machine Learning to estimate the price of a laptop based on these specifications.

The trained Machine Learning pipeline is integrated with an interactive Streamlit application, allowing users to enter laptop specifications and receive a real-time price prediction.

### 🔄 Project Workflow

```text
Raw Dataset
     ↓
Data Cleaning
     ↓
Exploratory Data Analysis
     ↓
Feature Engineering
     ↓
Data Preprocessing
     ↓
Train/Test Split
     ↓
Model Training
     ↓
Model Evaluation
     ↓
Pipeline Serialization
     ↓
Streamlit Deployment
```

---

## ✨ Features

* 🏢 Select laptop brand
* 💻 Select laptop type
* 🧠 Select RAM
* ⚖️ Enter laptop weight
* 🖥️ Select touchscreen availability
* 🎨 Select IPS display
* 📐 Enter screen size
* ⚙️ Select CPU
* 🎮 Select GPU
* 🪟 Select operating system
* 💾 Specify storage configuration
* 📊 Calculate Pixel Density (PPI)
* 💰 Get an estimated laptop price

---

## 🛠️ Technologies Used

| Technology       | Purpose                             |
| ---------------- | ----------------------------------- |
| **Python**       | Programming language                |
| **Pandas**       | Data manipulation and preprocessing |
| **NumPy**        | Numerical operations                |
| **Scikit-learn** | Machine Learning and preprocessing  |
| **Matplotlib**   | Data visualization                  |
| **Seaborn**      | Exploratory Data Analysis           |
| **Streamlit**    | Web application and deployment      |
| **Pickle**       | Model and pipeline serialization    |

---

## 🤖 Machine Learning

The project uses a Scikit-learn regression pipeline for preprocessing and price prediction.

### Data Preprocessing

The dataset contains both numerical and categorical features.

Categorical features are transformed using **OneHotEncoder**, while numerical features are processed before being passed to the regression model.

The complete trained pipeline is saved as:

```text
pipe.pkl
```

This ensures that the same preprocessing steps used during training are applied when users make predictions through the Streamlit application.

---

## 📊 Features Used

The model uses the following laptop specifications:

* Company / Brand
* Laptop Type
* RAM
* Weight
* Touchscreen
* IPS Display
* Screen Size
* CPU
* GPU
* Operating System
* HDD Storage
* SSD Storage
* Hybrid Storage
* Flash Storage
* Pixel Density (PPI)

---

## 📁 Project Structure

```text
Laptop-Price-Predictor/
│
├── app.py
├── Laptop_Price_Prediction.ipynb
├── laptop_data.csv
├── pipe.pkl
├── df.pkl
├── requirements.txt
├── README.md
└── .gitignore
```

### File Description

| File                            | Description                                    |
| ------------------------------- | ---------------------------------------------- |
| `app.py`                        | Streamlit application for price prediction     |
| `Laptop_Price_Prediction.ipynb` | Complete Machine Learning development notebook |
| `laptop_data.csv`               | Dataset used for model development             |
| `pipe.pkl`                      | Serialized trained Machine Learning pipeline   |
| `df.pkl`                        | Processed dataframe used by the application    |
| `requirements.txt`              | Required Python dependencies                   |
| `.gitignore`                    | Files and folders ignored by Git               |

---

## ⚙️ Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/v4763442-creator/Laptop-Price-Predictor.git
```

### 2. Navigate to the project directory

```bash
cd Laptop-Price-Predictor
```

### 3. Install the required dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Streamlit application

```bash
streamlit run app.py
```

The application will open in your default web browser.

---

## ☁️ Deployment

The application is deployed using **Streamlit Community Cloud**.

🔗 **Live Application:**
https://laptop-price-predictor-7bdqkdfk4tmc2tbjcyjmjma.streamlit.app/

The application source code, trained pipeline, preprocessing objects, and project notebook are maintained in this repository.

---

## 📈 Future Improvements

* Compare multiple regression algorithms
* Perform systematic hyperparameter tuning
* Improve prediction performance
* Add model performance visualizations
* Provide a prediction price range
* Improve the user interface and experience
* Add laptop recommendation functionality
* Add additional laptop specifications and updated market data

---

## 👨‍💻 Author

**Vivek**

🔗 GitHub:
https://github.com/v4763442-creator

🔗 Live Project:
https://laptop-price-predictor-7bdqkdfk4tmc2tbjcyjmjma.streamlit.app/

---

⭐ If you found this project useful, consider giving the repository a star!
