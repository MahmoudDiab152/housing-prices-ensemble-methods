# 🏡 California Housing Price Prediction using Ensemble Learning

This project aims to predict housing prices in California using various regression models with a focus on **ensemble methods** such as Random Forest, XGBoost, Voting Regressor, and Stacking Regressor. The models are trained and evaluated on the California Housing dataset, which includes demographic and geographic data from the 1990 U.S. Census.

---

## 📁 Dataset

- **Source:** California Housing Dataset (from the UCI Machine Learning Repository or available in `sklearn.datasets`)
- **Features:** Median income, total rooms, total bedrooms, population, ocean proximity, etc.
- **Target:** Median house value

---

## 🔧 Features & Workflow

- Data Cleaning & Preprocessing
- Feature Engineering (custom ratio features)
- Categorical Encoding (One-Hot Encoding)
- Model Training (Decision Tree, Random Forest, XGBoost, Stacking)
- Evaluation (MAE, RMSE, R² Score)
- Performance Comparison of Models

---

## 📦 Libraries Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost

---

## 📊 Results Summary

| Model                 | RMSE   | MAE      | R² Score |
|----------------------|--------|----------|----------|
| Decision Tree        | ~0.66  | ~32,298  | ~48,126  |
| Random Forest        | ~0.82  | ~23,772  | ~34,810  |
| XGBoost              | ~0.83  | ~23,091  | ~34,109  |
| Stacking Regressor   | ~0.83  | ~23,376  | ~34,121  |

---

## 📌 Conclusion

Ensemble models (particularly **XGBoost** and **Stacking**) outperformed individual regressors, offering better generalization and predictive accuracy on the housing price data.

---
