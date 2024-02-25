# Ola Driver Churn Prediction

## Problem Statement

Recruiting and retaining drivers is a significant challenge for Ola due to high churn rates. This project aims to predict driver attrition based on various attributes such as demographics, tenure information, and historical performance data.

## Dataset

- **Dataset Link:** [Ola Driver Dataset](https://d2beiqkhq929f0.cloudfront.net/public_assets/assets/000/002/492/original/ola_driver_scaler.csv)
- **Column Features:**
  - `MMM-YY`
  - `Driver_ID`
  - `Age`
  - `Gender`
  - `City`
  - `Education_Level`
  - `Income`
  - `Dateofjoining`
  - `LastWorkingDate`
  - `Joining Designation`
  - `Grade`
  - `Total Business Value`
  - `Quarterly Rating`

## Exploratory Data Analysis (EDA)

1. Import the dataset and perform exploratory analysis steps.
2. Convert date-like features to their respective data type.
3. Check for missing values and prepare data for KNN Imputation.
4. Aggregate data to remove multiple occurrences of the same driver data.

## Feature Engineering

1. Create a column indicating whether the quarterly rating has increased.
2. Target variable creation: Create a column named 'target' indicating whether the driver has left the company.
3. Create a column indicating whether the monthly income has increased.

## Statistical Summary

Provide a summary of the derived dataset, including key statistics and insights.

## Correlation Analysis

Check correlation among independent variables and understand their interactions.

## Data Preprocessing

1. One-hot encoding of categorical variables.
2. Treatment of class imbalance.
3. Standardization of training data.

## Ensemble Learning - Bagging and Boosting

Apply ensemble learning methods with hyper-parameter tuning.

## Results Evaluation

1. Classification Report.
2. ROC AUC Curve.

## Actionable Insights & Recommendations

Provide actionable insights and recommendations based on the analysis.

## Additional Features

- **Feature Importance:** Analyze and display the importance of different features.
- **Visualizations:** Include relevant visualizations to support your findings.
- **Model Interpretability:** Explain the key factors contributing to predictions.

---

Feel free to customize the template based on your project specifics. Include links to code files, visualizations, and any additional resources.
