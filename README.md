# Portuguese Bank Marketing Campaign

This project analyzes marketing campaign data from a Portuguese bank to predict whether a customer will subscribe to a term deposit. The goal was to explore the data, engineer features, and build classification models to maximize marketing efficiency.

---

## Overview

- Dataset: [UCI Portuguese Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing)
- Problem Type: Binary Classification (`yes`/`no`)
- Target: Customer subscription to term deposit
- Tools: Python, Pandas, Scikit-learn, XGBoost, Matplotlib, Seaborn

---

## File Structure

| File/Folder                                 | Description                                                  |
|--------------------------------------------|--------------------------------------------------------------|
| [`1_EDA_PortugueseBank.ipynb`](https://nbviewer.org/github/DarshiniMH/Portugese-Bank-Marketing-Campaign/blob/47a9d3e82bfa34665ec76d3e0fff4700e1cfc313/EDA_PortugeseBank.ipynb#binning-numeric-features-into-buckets)            | Notebook for data loading, cleaning, univariate and bivariate EDA |
| [`2_Modeling_PortugueseBank.ipynb`](https://nbviewer.org/github/DarshiniMH/Portugese-Bank-Marketing-Campaign/blob/47a9d3e82bfa34665ec76d3e0fff4700e1cfc313/Feature_Engineering_Modeling_PortugeseBank.ipynb) | Notebook for feature engineering, model training, tuning, and evaluation |
| [`train_data.csv`](./train_data.csv)                             | Cleaned training dataset used for modeling                   |
| [`test_data.csv`](./test_data.csv)                               | Cleaned testing dataset used for evaluation                  |
| [`Portugese_bank_marketing_v2.ipynb`](./Portugese_bank_marketing_v2.ipynb) | Original combined notebook (EDA + modeling) — now archived   |
| [`README.md`](./README.md)  

---

## Key Steps

-  Data Cleaning & Exploration
-  Categorical Encoding & Feature Engineering
-  Binning numeric variables for interpretability
-  Logistic Regression, Random Forest, and XGBoost modeling
-  ROC-AUC evaluation
-  Profit-based threshold tuning

---

## Highlights

- Achieved ROC AUC score of ~93.5
- Identified top 20 influential features for targeting
- Designed a profitability-aware evaluation strategy


---

##  Acknowledgments

- UCI Machine Learning Repository

