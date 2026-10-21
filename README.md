# Titanic Survival Prediction

An end-to-end machine learning project developed for the Kaggle Titanic competition.

## Project Overview

The goal is to predict passenger survival using demographic, ticket, and family-related information.

## Workflow

- Data exploration and visualization (EDA)
- Data cleaning and missing-value handling
- Feature engineering, including family and ticket groups
- Data preprocessing with scikit-learn pipelines
- Model evaluation using repeated stratified cross-validation
- Random Forest model training and Kaggle submission

## Model Performance

| Metric | Result |
|---|---|
| Cross-Validation Accuracy | 84.21% |
| Kaggle Public Leaderboard Accuracy | 79.19% |
| Final Model | Random Forest |

## Tools & Libraries

Python, Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn.

## Kaggle Notebook

https://www.kaggle.com/code/abdullahalkamel/titanic-final#%F0%9F%9A%A2-Titanic-Survival-Prediction

## Dataset

[Kaggle Titanic — Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic)

## How to Run

Open the Jupyter Notebook in Kaggle, attach the Titanic competition dataset, and run all cells.

## Key Takeaway

Feature engineering and careful validation were essential to improving predictive performance. Expanding family and ticket group features produced the strongest model in this project.
