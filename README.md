# 🎓 Student Performance Prediction System

An End-to-End Machine Learning Project that predicts a student's **Math Score** based on demographic and academic factors such as gender, ethnicity, parental education, lunch type, test preparation course, reading score, and writing score.

## 🚀 Live Demo

**Deployed Application:**
https://mlproject-gkvm.onrender.com

---

## 📌 Project Overview

This project implements a complete Machine Learning pipeline from data ingestion to deployment.

The system takes student information as input and predicts the expected mathematics score using a trained machine learning model.

---

## ✨ Features

* Data Ingestion Pipeline
* Data Transformation Pipeline
* Feature Engineering
* Model Training
* Hyperparameter Tuning using GridSearchCV
* Model Evaluation
* Prediction Pipeline
* Flask Web Application
* Logging & Exception Handling
* Deployment on Render

---

## 🛠️ Tech Stack

### Programming Language

* Python

### Machine Learning

* Scikit-Learn
* XGBoost
* CatBoost

### Data Processing

* Pandas
* NumPy

### Web Framework

* Flask

### Deployment

* Render

### Version Control

* Git
* GitHub

---

## 📂 Project Structure

```text
mlproject/
│
├── artifacts/
│   ├── model.pkl
│   └── preprocessor.pkl
│
├── notebook/
│
├── src/
│   ├── components/
│   │   ├── data_ingestion.py
│   │   ├── data_transformation.py
│   │   └── model_trainer.py
│   │
│   ├── pipeline/
│   │   └── predict_pipeline.py
│   │
│   ├── exception.py
│   ├── logger.py
│   └── utils.py
│
├── templates/
│   ├── home.html
│   └── index.html
│
├── app.py
├── requirements.txt
├── setup.py
├── Procfile
└── README.md
```

---

## 📊 Machine Learning Workflow

### 1. Data Ingestion

* Reads dataset
* Splits data into training and testing sets
* Stores datasets in artifacts folder

### 2. Data Transformation

* Handles missing values
* Performs feature encoding
* Applies scaling using pipelines
* Saves preprocessor object

### 3. Model Training

Multiple regression models are trained and evaluated:

* Linear Regression
* Ridge Regression
* Lasso Regression
* Decision Tree Regressor
* Random Forest Regressor
* Gradient Boosting Regressor
* AdaBoost Regressor
* XGBoost Regressor
* CatBoost Regressor
* K-Nearest Neighbors Regressor

### 4. Hyperparameter Tuning

* GridSearchCV is used to identify the best parameters.
* Best-performing model is selected automatically.

### 5. Prediction Pipeline

* Loads trained model and preprocessor.
* Transforms incoming user data.
* Generates real-time predictions.

---

## 🖥️ Web Application

Users can enter:

* Gender
* Race/Ethnicity
* Parental Education Level
* Lunch Type
* Test Preparation Course
* Reading Score
* Writing Score

The system predicts the expected **Math Score** instantly.

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/Isha4002/mlproject.git
```

### Move to Project Folder

```bash
cd mlproject
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

```bash
venv\Scripts\activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
python app.py
```

Open:

```text
http://127.0.0.1:5000
```

---

## 🎯 Learning Outcomes

Through this project, I gained hands-on experience in:

* Machine Learning Model Development
* Feature Engineering
* Data Pipelines
* Hyperparameter Optimization
* Flask Development
* Model Deployment
* Software Engineering Practices
* Git & GitHub Workflow

---

## 👩‍💻 Author

**Isha Pal**

* GitHub: https://github.com/Isha4002

---

⭐ If you found this project useful, consider giving it a star on GitHub.

