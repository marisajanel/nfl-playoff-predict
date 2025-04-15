# 🏈 NFL Playoff Predictor (2018–2023)

This project uses team-level regular season data from the 2018–2023 NFL seasons to predict whether a team made the playoffs. We trained and compared two machine learning models — Logistic Regression and Random Forest — to analyze what regular season stats are most indicative of postseason qualification.

---

## 📊 Project Overview

**Objective**:  
Predict whether an NFL team made the playoffs using only regular season statistics.

**Models Used**:
- Logistic Regression (with hyperparameter tuning using GridSearchCV)
- Random Forest Classifier

**Evaluation Metrics**:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Feature Importance

---

## 🔍 Key Findings

- **Margin of Victory**, **Team Rating**, and **Offensive Performance** were strong predictors of playoff success.
- After tuning, **Logistic Regression reached 89.7% accuracy**, performing slightly better than the baseline model.
- **Random Forest had the highest precision and F1 score**, making it more reliable in reducing false positives.
- Both models showed strong recall, successfully identifying most playoff teams.

---
