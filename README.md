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

| File/Folder | Description |
|-------------|-------------|
| [`Portugese_bank_marketing_POLISHED.ipynb`](https://nbviewer.org/github/DarshiniMH/Portugese-Bank-Marketing-Campaign/blob/main/Portugese_bank_marketing_POLISHED.ipynb) | Cleaned Jupyter notebook with full EDA, modeling, and evaluation |
| `train_test_split.pkl` | Pickled train/test split for fast reuse |
| `README.md` | You're reading it! Contains project summary and links |

---

## Key Steps

- 🔹 Data Cleaning & Exploration
- 🔹 Categorical Encoding & Feature Engineering
- 🔹 Binning numeric variables for interpretability
- 🔹 Logistic Regression, Random Forest, and XGBoost modeling
- 🔹 ROC-AUC evaluation
- 🔹 Profit-based threshold tuning

---

## Highlights

- Achieved **ROC AUC score of ~93.5
- Identified top 20 influential features for targeting
- Designed a profitability-aware evaluation strategy

---

## View Notebook

[View on nbviewer](https://nbviewer.org/github/DarshiniMH/Portugese-Bank-Marketing-Campaign/blob/main/Portugese_bank_marketing_POLISHED.ipynb)

---

##  Acknowledgments

- UCI Machine Learning Repository

