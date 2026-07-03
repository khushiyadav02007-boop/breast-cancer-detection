# Breast Cancer Detection — ML Classification Project

A machine learning project to classify breast tumors as malignant or benign based on cell nucleus characteristics, using the Breast Cancer Wisconsin (Diagnostic) Dataset.

## Objective
Build and compare multiple classification models to accurately predict whether a breast tumor is malignant (M) or benign (B), with a focus on minimizing false negatives — since missing a malignant tumor is the most critical error in medical diagnosis.

## Dataset
- **Source:** Breast Cancer Wisconsin (Diagnostic) Dataset
- **Samples:** 569
- **Features:** 30 numeric features describing cell nucleus characteristics (radius, texture, perimeter, area, smoothness, concavity, etc.)
- **Target:** M = Malignant, B = Benign

## Steps Covered
1. Data Collection and Initial Exploration — shape, info, describe, null check, duplicate check
2. Data Preprocessing — dropped id and Unnamed: 32 columns, handled class imbalance with SMOTE, label encoding
3. Exploratory Data Analysis — distribution analysis, class balance check, correlation analysis
4. Visualization — countplot, boxplot, histplot, scatterplot, barplot, heatmap, pairplot
5. Feature Scaling — StandardScaler
6. Model Training — Logistic Regression, Decision Tree, Random Forest, SVM
7. Model Evaluation — accuracy, F1 score, classification report, confusion matrix

## Results

| Model | Accuracy | F1 Score |
|---|---|---|
| Support Vector Machine | 98.25% | 0.976 |
| Logistic Regression | 97.37% | 0.964 |
| Random Forest | 97.37% | 0.963 |
| Decision Tree | 93.86% | 0.920 |

**Best Model: Support Vector Machine — 98.25% accuracy**

## Tech Stack
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Imbalanced-learn (SMOTE)

## How to Run
1. Clone the repository
2. Install dependencies:
   pip install pandas numpy scikit-learn matplotlib seaborn imbalanced-learn jupyter
3. Open the notebook:
   jupyter notebook Breast_cancer.ipynb

## Built by
Khushi Yadav — [GitHub](https://github.com/khushiyadav02007-boop) | [LinkedIn](https://linkedin.com/in/khushi-yadav-b737043a1)
