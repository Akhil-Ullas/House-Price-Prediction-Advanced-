

# 🏠 House Price Prediction – Advanced Regression

This project focuses on building an **end-to-end regression pipeline for house price prediction**, covering data preprocessing, feature engineering, model training, model comparison, and evaluation.

The goal is to understand how different preprocessing strategies and regression algorithms affect predictive performance on structured tabular data.

---

## 📌 Tools & Libraries

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* scikit-learn
* XGBoost

---

## ⚙️ Data Preprocessing & Feature Engineering

* Analyzed training and test datasets
* Handled missing values using column dropping and mean/mode imputation
* Separated numerical and categorical features
* Encoded categorical variables using Label Encoding
* Applied feature scaling using StandardScaler
* Removed ID and non-informative columns

---

## 🤖 Models Implemented & Compared

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* AdaBoost Regressor
* Gradient Boosting Regressor
* XGBoost Regressor
* K-Nearest Neighbors Regressor
* Support Vector Regressor (SVR)

---

## 🏆 Model Selection & Performance

* Compared multiple models on validation performance
* **Gradient Boosting Regressor selected as final model**
* Achieved approximately **80% validation accuracy**

*(Note: Accuracy refers to validation score; regression metrics such as R² or RMSE are more appropriate and can be added later.)*

---

## ✅ Key Takeaways

* Data preprocessing strongly influences regression performance
* Ensemble models outperform single estimators on tabular data
* Feature scaling benefits distance-based and margin-based models
* Model comparison is essential before final selection

