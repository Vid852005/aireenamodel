# 🧠 LightGBM Classification Model

## 📌 Project Overview

This project builds a supervised machine learning classification model
to predict the **`Class`** label using structured tabular data.

The model is trained using **LightGBM** and evaluated using the
**F1-score** metric.

------------------------------------------------------------------------

## 📂 Dataset Description

-   `TRAIN.csv` → Training features + target column `Class`
-   `TEST.csv` → Test features with `ID` column

### Target Variable

-   `Class` → Binary classification label

------------------------------------------------------------------------

## ⚙️ Model Details

-   Algorithm: LightGBM (Gradient Boosted Decision Trees)
-   Validation Strategy: Stratified K-Fold Cross Validation
-   Feature Scaling: StandardScaler
-   Evaluation Metric: F1-score

------------------------------------------------------------------------

## 📊 Evaluation Metric

F1-score balances Precision and Recall:

F1 = 2 × (Precision × Recall) / (Precision + Recall)

This metric is useful for handling imbalanced datasets.

------------------------------------------------------------------------

## 🔄 Training Pipeline

1.  Load dataset
2.  Split features and target
3.  Apply scaling
4.  Perform Stratified K-Fold training
5.  Train LightGBM model
6.  Evaluate using F1-score
7.  Generate predictions for test set

------------------------------------------------------------------------

## 🚀 How to Run

Install dependencies:

    pip install pandas numpy scikit-learn lightgbm

Run the notebook:

    jupyter notebook competition.ipynb

------------------------------------------------------------------------

## 📌 Conclusion

This project demonstrates an efficient LightGBM pipeline optimized for
F1-score performance on tabular classification data.
