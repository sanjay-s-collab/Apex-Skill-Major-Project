# Apex Skill Major Project


**Name:** Sanjay S  
**Domain:** Artificial Intelligence  
**Project:** Apex Skill Major Project  
**Batch:** July 2026

---

## Overview

This repository contains two machine learning projects developed as part of the Apex Skill Major Project.

The projects focus on applying machine learning regression techniques to real-world prediction problems.

### Projects Included

1. **Crop Yield Prediction – Theme 8**
2. **Insurance Premium Cost Prediction – Theme 6**

Both projects include data preprocessing, feature engineering, multiple regression models, model evaluation, trained model files, notebooks, and result visualizations.

---

# 1. Crop Yield Prediction – Theme 8

## Problem Statement

Crop yield is influenced by several environmental and agricultural factors such as rainfall, temperature, pesticide usage, location, crop type, and year.

The objective of this project is to develop machine learning models that can predict crop yield based on these factors.

## Dataset

The dataset contains agricultural information including:

- Area
- Crop Item
- Year
- Average Rainfall
- Pesticides Used
- Average Temperature
- Crop Yield

### Dataset Size

- Records: 28,242
- Features: 7 after preprocessing/cleaning

## Machine Learning Models

The following regression models were developed and evaluated:

- Multiple Linear Regression
- Polynomial Regression
- Decision Tree Regressor
- Random Forest Regressor

## Best Model

**Random Forest Regressor**

### Performance

| Metric | Result |
|---|---:|
| R² Score | 0.9832 |
| MAE | 4231.45 |
| RMSE | 11036.94 |

The Random Forest Regressor achieved the best overall performance among the evaluated models.

---

# 2. Insurance Premium Cost Prediction – Theme 6

## Problem Statement

Insurance premium costs depend on several factors such as age, gender, BMI, number of children, smoking status, and region.

The objective of this project is to develop machine learning models that can predict insurance premium costs using customer-related features.

## Dataset

The project uses an insurance dataset containing demographic and health-related attributes used for predicting insurance charges.

## Machine Learning Models

The following regression models were developed and evaluated:

- Multiple Linear Regression
- Polynomial Regression
- Decision Tree Regressor
- Random Forest Regressor

## Best Model

**Random Forest Regressor**

### Performance

| Metric | Result |
|---|---:|
| R² Score | 0.8828 |
| MAE | 2574.23 |
| RMSE | 4641.42 |

The Random Forest Regressor achieved the best overall performance among the evaluated models.

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Git
- GitHub
- Git LFS

---

# Model Evaluation

The models were evaluated using the following metrics:

### R² Score

Measures how well the model explains the variation in the target variable.

### Mean Absolute Error (MAE)

Measures the average absolute difference between actual and predicted values.

### Root Mean Squared Error (RMSE)

Measures the square root of the average squared prediction error.

---

# Results Summary

| Project | Best Model | R² | MAE | RMSE |
|---|---|---:|---:|---:|
| Crop Yield Prediction | Random Forest Regressor | 0.9832 | 4231.45 | 11036.94 |
| Insurance Premium Cost Prediction | Random Forest Regressor | 0.8828 | 2574.23 | 4641.42 |

---
# Conclusion

Both projects demonstrate the application of machine learning regression techniques to real-world prediction problems.

Among the evaluated models, the Random Forest Regressor achieved the best performance for both Crop Yield Prediction and Insurance Premium Cost Prediction.

The projects include complete notebooks, trained models, datasets, and result visualizations for evaluation and reproducibility.



# Author
  Sanjay S



# Repository Structure

```text
Apex-Skill-Major-Project/
│
├── Crop_Yield_Prediction/
│   ├── data/
│   │   └── yield_df.csv
│   ├── models/
│   │   ├── decision_tree.pkl
│   │   ├── linear_regression.pkl
│   │   ├── polynomial_regression.pkl
│   │   └── random_forest.pkl
│   ├── notebooks/
│   │   └── crop_yield_analysis.ipynb
│   └── results/
│       ├── comparison_table.png
│       ├── feature_importance.png
│       └── prediction_plot.png
│
├── Insurance_Premium_Cost_Prediction/
│   ├── data/
│   │   └── insurance.csv
│   ├── models/
│   │   ├── decision_tree.pkl
│   │   ├── linear_regression.pkl
│   │   ├── polynomial_regression.pkl
│   │   └── random_forest.pkl
│   ├── notebooks/
│   │   └── insurance_analysis.ipynb
│   └── results/
│       ├── comparison_table.png
│       ├── feature_importance.png
│       └── prediction_plot.png
│
└── README.md

