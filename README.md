# LightGBM Classification Model

## Project Overview
This project implements a supervised machine learning pipeline to predict the **Class** label from structured tabular data.
The model is built using **LightGBM** and evaluated with the **F1-score** metric.

---

## Dataset
- TRAIN.csv: Training features and target column `Class`
- TEST.csv: Test features with `ID` column

Target:
- Class (binary)

---

## Model Description
- Algorithm: LightGBM (Gradient Boosted Decision Trees)
- Validation: Stratified K-Fold Cross Validation
- Feature Scaling: StandardScaler
- Metric: F1-score

---

## Training Pipeline
1. Load data
2. Feature-target split
3. Feature scaling
4. Stratified K-Fold training
5. F1-score evaluation
6. Test prediction

---

## How to Run
pip install pandas numpy scikit-learn lightgbm

jupyter notebook competition.ipynb

---

## Conclusion
A clean and efficient LightGBM classification pipeline optimized for F1-score.
