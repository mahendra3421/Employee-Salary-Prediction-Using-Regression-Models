# 💼 Employee Salary Prediction Using Regression Models

This project focuses on predicting the annual compensation of developers using machine learning regression techniques. The data is sourced from the [Stack Overflow Annual Developer Survey](https://insights.stackoverflow.com/survey). The goal is to explore how various factors such as country, job role, education, and employment type influence salary and to build a model that accurately predicts salaries based on these features.

---

## 📊 Dataset

- **Source**: [Stack Overflow Developer Survey](https://insights.stackoverflow.com/survey)
- The dataset contains a wide range of features related to developers worldwide, including demographic details, education, work experience, and compensation.
- For this project, we have selected a subset of relevant features and cleaned the data to suit a regression task.

---

## 🎯 Problem Statement

The objective is to predict the **annual salary (in USD)** of a developer based on their:
- Country
- Developer Type
- Education Level
- Employment Type

This is treated as a **supervised regression problem**, and multiple machine learning models are tested to find the best-performing one.

---

## 🔧 Features Used

- `Country`: Country of residence.
- `Developer Type`: Role or specialization (e.g., Data Scientist, Web Developer).
- `Education Level`: Highest degree or qualification.
- `Employment Type`: Full-time, part-time, freelance, etc.
- `Annual Compensation (USD)`: Target variable.

---

## ⚙️ Technologies & Libraries Used

- Python 3.7+
- Pandas, NumPy – Data manipulation
- Matplotlib, Seaborn – Visualization
- Scikit-learn – Regression models & preprocessing
- XGBoost – Advanced regression
- Joblib – Model persistence
- Streamlit – Web application for deployment

---

## 🧠 ML Workflow

1. Problem Understanding
2. Data Cleaning & Preprocessing
3. Feature Encoding (Label Encoding / One-Hot Encoding)
4. Model Building (Linear Regression, Random Forest, XGBoost)
5. Model Evaluation (RMSE, R²)
6. Hyperparameter Tuning
7. Saving the best model
8. Deploying the model using Streamlit


