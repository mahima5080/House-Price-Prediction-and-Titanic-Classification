# House Price Prediction & Titanic Survival Classification

## 📌 Overview
This repository contains the **Week 2 Machine Learning Foundations** assignment. It covers two fundamental supervised machine learning tasks:
1. **Linear Regression**: A regression model to predict continuous house prices based on structural and location features.
2. **Logistic Regression**: A classification model to predict passenger survival on the Titanic.

---

## 🛠️ Assignment Tasks & Objectives

### 1. House Price Prediction (Linear Regression)
* **Goal**: Build and evaluate a regression model to predict continuous housing values.
* **Key Steps**:
  * Cleaned and encoded categorical features (`mainroad`, `basement`, `furnishingstatus`, etc.).
  * Split data into **80% Training** and **20% Testing** sets using `train_test_split`.
  * Trained a `LinearRegression` model using Scikit-Learn.
  * Evaluated performance using **$R^2$ Score** and **Root Mean Squared Error (RMSE)**.
  * Plotted Actual vs. Predicted house prices using `Matplotlib`.

### 2. Titanic Survival Prediction (Logistic Regression)
* **Goal**: Build a binary classification model to predict passenger survival (`0` = Did not survive, `1` = Survived).
* **Key Steps**:
  * Imputed missing values in `Age` (median) and `Embarked` (mode).
  * Applied `LabelEncoder` for binary text (`Sex`) and `One-Hot Encoding` for categorical ports (`Embarked`).
  * Trained a `LogisticRegression` model.
  * Evaluated overall accuracy and generated a **Confusion Matrix** heatmap using `Seaborn`.

---

## 📈 Model Performance & Results

| Model | Task Type | Evaluation Metric | Result |
| :--- | :--- | :--- | :--- |
| **Linear Regression** | Regression | $R^2$ Score | **~0.65** |
| **Logistic Regression** | Binary Classification | Accuracy Score | **~81.0%** |

---

## 🚀 How to Run the Project Locally

1. **Clone the Repository**:
   ```bash
   git clone [https://github.com/mahima5080/House-Price-Prediction-and-Titanic-Classification.git](https://github.com/mahima5080/House-Price-Prediction-and-Titanic-Classification.git)
   cd House-Price-Prediction-and-Titanic-Classification
