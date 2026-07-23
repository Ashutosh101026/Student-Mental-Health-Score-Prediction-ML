# Student Mental Health Score Prediction using Machine Learning

## Overview

This project predicts students' mental health scores based on their social media usage, academic performance, and lifestyle factors using machine learning regression techniques. It demonstrates a complete end-to-end machine learning workflow, including data preprocessing, feature engineering, model building, hyperparameter tuning, and performance evaluation.

---

## Dataset

The dataset contains student-related information, including:

- Age
- Gender
- Country
- Academic Level
- Social Media Platform
- Purpose of Social Media Usage
- Daily Usage Hours
- Daily Unlock Count
- Study Hours
- Physical Activity
- Sleep Hours
- Stress Level

**Target Variable:**

- Mental Health Score

---

## Project Workflow

- Data Loading
- Exploratory Data Analysis (EDA)
- Missing Value Analysis
- Duplicate Record Detection
- Feature Selection
- Train-Test Split
- Feature Engineering
- Data Preprocessing
- Model Training
- Hyperparameter Tuning
- Model Evaluation

---

## Data Preprocessing

Implemented an end-to-end preprocessing pipeline using Scikit-Learn.

### Numerical Features
- StandardScaler

### Skewed Features
- Log Transformation
- StandardScaler

### Ordinal Features
- Ordinal Encoding

### Categorical Features
- One-Hot Encoding

### Pipeline Components
- ColumnTransformer
- Pipeline

---

## Machine Learning Models

- Linear Regression
- Random Forest Regressor

The Random Forest model was further optimized using **RandomizedSearchCV** to identify the best combination of hyperparameters and improve predictive performance.

---

## Model Evaluation

Performance was evaluated using:

- R² Score
- Mean Absolute Error (MAE)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## Project Highlights

- End-to-End Machine Learning Pipeline
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Preprocessing
- ColumnTransformer
- Scikit-Learn Pipeline
- One-Hot Encoding
- Ordinal Encoding
- Feature Scaling
- Log Transformation
- Multiple Regression Models
- Hyperparameter Tuning using RandomizedSearchCV
- Model Comparison
- Predictive Analytics

---

## Future Improvements

- Implement XGBoost, LightGBM, and CatBoost
- Perform Cross-Validation
- Deploy the model using Streamlit or Flask
- Save the trained model using Joblib
- Build an interactive prediction dashboard

---

