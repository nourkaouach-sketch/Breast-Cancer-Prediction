# Breast Cancer Prediction Pipeline

Machine Learning pipeline for breast cancer diagnosis using feature selection techniques, class balancing, explainable AI and model comparison.

## Dataset
Dataset: Wisconsin Breast Cancer Dataset (scikit-learn)<br>
569 observations<br>
30 features<br>
Binary classification

## Techniques 
- Exploratory Data Analysis (EDA)
- Standardization
- PCA visualization
- Feature Selection
    - ANOVA F-score
    - Mutual Information
    - Forward Selection
    - Backward Elimination
    - LASSO
- SMOTE
- Logistic Regression
- Random Forest
- XGBoost
- Cross-validation
- Precision-Recall Curves
- SHAP Explainability

## Project Structure

```
Breast-Cancer-Prediction/
│
├── breast_cancer_prediction_pipeline.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## Limitations

- Dataset relatively small (569 samples).
- Results are not intended for clinical use.
- External validation on independent datasets would be required.

## Conclusion

Several machine learning models and feature selection methods were evaluated for breast cancer prediction.

This project illustrates a complete machine learning workflow including preprocessing, feature selection, class balancing, model evaluation and explainable AI.




