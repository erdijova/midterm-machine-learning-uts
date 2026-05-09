# Fraud Detection Machine Learning Project

## 📌 Project Overview

This project is an end-to-end Machine Learning pipeline developed for fraud detection on online transactions. The goal of this project is to predict the probability that a transaction is fraudulent (`isFraud`) using machine learning techniques.

The workflow includes:

* Data preprocessing
* Missing value handling
* Feature engineering
* Handling class imbalance using SMOTE
* Model training using XGBoost
* Hyperparameter tuning using Optuna
* Model evaluation
* Experiment tracking using MLflow
* Fraud probability prediction

---

## 📂 Dataset

The dataset used in this project contains online transaction information such as:

* Transaction amount
* Product code
* Card information
* Email domain
* Device information
* Address information

### Files

* `train_transaction.csv`
* `test_transaction.csv`

Target variable:

* `isFraud`

  * `0` = Non-Fraud
  * `1` = Fraud

---

## 🛠️ Technologies & Libraries

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Optuna
* MLflow
* Matplotlib
* Seaborn
* Imbalanced-learn (SMOTE)

---

## ⚙️ Machine Learning Workflow

### 1. Data Preprocessing

* Handling missing values
* Label encoding categorical features
* Removing columns with high missing percentage

### 2. Handling Imbalanced Dataset

* SMOTE (Synthetic Minority Oversampling Technique)

### 3. Model Training

* XGBoost Classifier

### 4. Hyperparameter Tuning

* Optuna optimization

### 5. Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC

### 6. MLflow Tracking

* Logging parameters
* Logging metrics
* Saving trained models

---

## 📊 Model Evaluation

The model was evaluated using:

* Confusion Matrix
* Classification Report
* ROC-AUC Score

The project successfully generated fraud probability predictions for test transactions.

---

## 📁 Project Structure

```bash
midterm-machine-learning/
│
├── fraud_detection.ipynb
├── submission.csv
├── README.md
├── mlruns/
│
├── data/
├── notebooks/
└── outputs/
```

---

## 🚀 How to Run

1. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost optuna mlflow imbalanced-learn
```

2. Run Jupyter Notebook

```bash
jupyter notebook
```

3. Open:

* `fraud_detection.ipynb`

---


* Name : ERDI JOVA PRADANA
* Class : TK-47-04
* NIM : 101032300027

---

## 📌 Conclusion

This project demonstrates the implementation of an end-to-end fraud detection system using Machine Learning techniques. The use of XGBoost, SMOTE, Optuna, and MLflow helps improve model performance and experiment tracking effectively.
