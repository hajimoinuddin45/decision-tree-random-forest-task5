# 🌲 Decision Tree & Random Forest – Heart Disease Prediction

This repository contains my solution for **Task 5**, where I used Decision Tree and Random Forest models to predict heart disease using a publicly available dataset.

---

## 🎯 Objective

- Build tree-based models for classification.
- Visualize decision trees and analyze overfitting.
- Interpret feature importance and compare models.

---

## 🛠 Tools & Libraries

- Python
- Pandas
- Scikit-learn
- Matplotlib, Seaborn

---

## ✅ What I Did

1. **Loaded** the Heart Disease dataset.
2. **Explored** missing values and performed basic checks.
3. **Trained** a `DecisionTreeClassifier` with limited depth.
4. **Visualized** the decision tree using `plot_tree`.
5. **Trained** a `RandomForestClassifier` and compared its accuracy.
6. **Evaluated** models with:
   - Accuracy
   - Classification Report
   - Confusion Matrix
   - Cross-Validation Score
7. **Plotted** feature importances to interpret important predictors.

---

## 📊 Results

- Random Forest performed better than the single Decision Tree.
- Cross-validation showed stable accuracy.
- Features like `cp` (chest pain) and `thal` had high importance.

---

## 🧠 What I Learned

- How decision trees split data based on entropy/information gain.
- Random Forests reduce overfitting via bagging.
- Feature importance tells which attributes are most predictive.
- Visualizations help in understanding the model decisions.

---

## 📁 Files Included

- `task5_decision_tree_random_forest.ipynb`
- `README.md`
- `heart.csv` (Dataset used – can be downloaded from UCI or Kaggle)

---

## 🔗 Dataset Source

[Heart Disease Dataset on Kaggle](https://www.kaggle.com/datasets/cherngs/heart-disease-cleveland-uci)

---

Feel free to try this notebook yourself and tweak the max depth or number of trees in the Random Forest! 🔍
