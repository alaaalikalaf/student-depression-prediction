# Student Depression Prediction

A machine learning project that predicts whether a student is experiencing depression, based on academic, lifestyle, financial and personal factors.

> Educational project only. It is not a medical diagnostic tool.

## What was done
- Data cleaning (missing values, invalid values, feature engineering, encoding)
- Exploratory data analysis with visualizations
- Baseline model: Logistic Regression
- Comparison of 4 models (Logistic Regression, Decision Tree, Random Forest, XGBoost) on 1%, 10% and 100% of the training data
- Hyperparameter tuning of Random Forest with GridSearchCV
- Saved pipelines for deployment

## Results (test set)
| Model | ROC-AUC | Recall | F1 |
|---|---|---|---|
| Baseline Logistic Regression | 0.924 | 0.89 | 0.87 |
| Tuned Random Forest | 0.923 | 0.886 | 0.874 |

## Dataset
"Student Depression Dataset" from Kaggle. Download the CSV and place it next to the notebook.

## How to run
```
pip install -r requirements.txt
jupyter notebook student_depression_analysis.ipynb
```

## Tools
Python, Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn
