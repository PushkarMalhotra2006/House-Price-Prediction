# House-Price-Prediction



Progress Update



✔ Data loading

✔ Exploratory Data Analysis

✔ Train-test split

✔ Missing value preprocessing

✔ Full preprocessing

✔ Encoding

✔ Baseline model

✔ Log transformation (major boost)

✔ Ridge

✔ Lasso

✔ Random Forest, Gradient Boosting, XGBoost comparisons

✔ XGBoost tuning

✔ Final conclusion (Lasso best)



\# 🏠 House Price Prediction (ML Project)



\## 📌 Overview



This project builds a machine learning model to predict house prices using the \*\*House Prices - Advanced Regression Techniques\*\* dataset from Kaggle.



The goal is to develop an end-to-end ML pipeline including data preprocessing, feature engineering, model training, and evaluation.



---



\## 🤖 Models Tried



\* Linear Regression

\* Ridge Regression (with hyperparameter tuning)

\* Lasso Regression (feature selection)

\* Random Forest Regressor

\* Gradient Boosting Regressor

\* XGBoost Regressor (with tuning)



---



\## 🏆 Final Model



\*\*Lasso Regression\*\*



\### 📊 Performance



\* \*\*RMSE:\*\* ~22,019

\* \*\*R² Score:\*\* ~0.936



---



\## 🔍 Key Insights



\* Log transformation of the target variable significantly improved model performance.

\* One-hot encoding increased feature dimensionality (~300 features).

\* Lasso regression removed ~96 irrelevant features, improving generalization.

\* Linear models outperformed tree-based models due to structured and linearized data.

\* Complex models (Random Forest, XGBoost) did not outperform simpler regularized models.



---



\## 🧠 Learnings



\* Data preprocessing and transformation can impact performance more than model complexity.

\* Feature selection is crucial in high-dimensional datasets.

\* Hyperparameter tuning improves model performance but depends on data characteristics.

\* Best model choice depends on dataset properties, not just algorithm complexity.



---



\## 🛠️ Tech Stack



\* Python

\* Pandas

\* NumPy

\* Seaborn

\* Scikit-learn

\* XGBoost

\* VS Code



---



\## 📁 Project Structure



```

house-price-prediction/

│

├── Dataset/

│   ├── data\_description.txt

│   └── train.csv

│

├── House-Price-Prediction.ipynb

├── lasso\_model.pkl

└── README.md

```

\## 📎 Dataset



Kaggle: House Prices - Advanced Regression Techniques



