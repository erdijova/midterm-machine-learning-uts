# Midterm Machine Learning Regression Project

## Predicting Song Release Year using Machine Learning

### Student Information
- Name: ERDI JOVA PRADANA
- Class: TK-47-04
- NIM: 101032300027

---

# Project Overview

This project was developed as part of the Midterm Assignment for the Machine Learning course.

The objective of this project is to build an end-to-end machine learning regression model capable of predicting the release year of a song based on audio features.

The dataset contains numerical audio feature values extracted from music signals.

---

# Dataset Information

- Dataset Name: midterm-regresi-dataset.csv
- Task Type: Regression
- Target Variable: Song Release Year
- Features: Numerical audio features

---

# Machine Learning Workflow

The project workflow includes:

1. Data Loading
2. Data Preprocessing
3. Feature Scaling
4. Train-Test Split
5. Random Forest Regression Model
6. Model Evaluation
7. Hyperparameter Tuning using Optuna
8. MLflow Tracking
9. LIME Interpretation

---

# Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- optuna
- lime
- mlflow

---

# Machine Learning Model

The regression model used in this project is:

- Random Forest Regressor

---

# Evaluation Metrics

The model was evaluated using regression metrics:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R² Score

---

# Hyperparameter Tuning

Optuna was used to optimize the Random Forest Regression hyperparameters in order to improve model performance.

---

# MLflow Tracking

MLflow was used to track:
- Model parameters
- Evaluation metrics
- Machine learning experiments

---

# LIME Interpretation

LIME was applied to explain the prediction results and identify the most influential audio features affecting the model predictions.

---

# Conclusion

The project successfully implemented an end-to-end machine learning regression pipeline for predicting song release years.

The Random Forest Regression model achieved good predictive performance after hyperparameter tuning using Optuna.

Additionally, MLflow and LIME helped improve experiment tracking and model interpretability.

---
