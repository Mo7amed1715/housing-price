# 🏡 Real Estate Price Prediction

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Ensemble_Learning-F7931E.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data_Wrangling-150458.svg)
![Status](https://img.shields.io/badge/Status-In_Progress-orange.svg)

An advanced regression model built to predict continuous housing prices based on high-dimensional property feature datasets.

## 📖 Project Overview
Real estate pricing is driven by dozens of overlapping variables, from square footage to neighborhood zoning. This project tackles the classic Kaggle Housing Prices dataset to accurately predict home sale prices.

To capture the complex, non-linear relationships between property features, the core engine relies on a **Random Forest Regressor**. 

## 🧠 Modeling Approach & Data Engineering
* **Algorithm:** Random Forest Regressor (Ensemble Learning)
* **Data Source:** Kaggle Housing Prices Dataset
* **Key Challenges Addressed:**
  * **Feature Alignment:** Engineered a robust pipeline to resolve dimensional mismatches (unequal column numbers) between the training and testing sets caused by one-hot encoding categorical variables.
  * **Missing Data:** Imputed missing values for numerical and categorical features using Pandas `apply()` and targeted aggregations.
  * **Ensemble Optimization:** Utilized Random Forest to automatically handle feature interactions and prevent overfitting on the training data.

## 🚀 How to Run

### 1. Install Dependencies
```bash
pip install pandas numpy scikit-learn
