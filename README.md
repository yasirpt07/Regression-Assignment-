# 🏠 California Housing Regression Analysis

This repository contains a machine learning regression project that uses the **California Housing Dataset** from `sklearn`. The objective is to apply and compare different regression algorithms and evaluate their performance on predicting median house values in California.

---

## 🎯 Objective

- Understand and implement various **supervised learning regression techniques**.
- Compare their performance using appropriate evaluation metrics.
- Gain hands-on experience with real-world data.

---

## 📁 Dataset

- **Source**: `sklearn.datasets.fetch_california_housing`
- **Description**: Contains information about various features of houses in California and their respective median prices.

---

## 🔧 Preprocessing Steps

- Converted the dataset into a **Pandas DataFrame** for better handling.
- Checked for and handled **missing values** (none found).
- Applied **StandardScaler** to normalize the feature values.
- Split the dataset into **training and testing sets** (80/20).

---

## 🤖 Implemented Regression Algorithms

| Algorithm                  | Description |
|---------------------------|-------------|
| Linear Regression         | Basic linear approach that models the relationship between features and target as a straight line. |
| Decision Tree Regressor   | Splits data into decision nodes for predicting non-linear relationships. |
| Random Forest Regressor   | Ensemble of decision trees to reduce overfitting and improve accuracy. |
| Gradient Boosting Regressor | Builds models sequentially to minimize error of the previous models. |
| Support Vector Regressor (SVR) | Uses hyperplanes to fit the best possible prediction line within a margin. Requires scaling. |

---

## 📊 Evaluation Metrics

Each model was evaluated using:

- **Mean Squared Error (MSE)**
- **Mean Absolute Error (MAE)**
- **R-squared Score (R²)**

---

## 🏆 Model Comparison

- **Best Performing Model**: ✅ Likely **Random Forest** or **Gradient Boosting**, due to strong performance on complex, non-linear data.
- **Least Performing Model**: ❌ Likely **SVR**, due to computational cost and sensitivity to scaling without tuning.

---

## 🧠 Libraries Used

- `scikit-learn`
- `pandas`
- `numpy`
- `matplotlib` / `seaborn` *(optional for visualizations)*

---


