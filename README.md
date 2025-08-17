# Ames House Price Analysis (Python)

## Overview
This project analyzes the **Ames Housing dataset** to identify key factors influencing residential property prices.  
Using **exploratory data analysis (EDA)**, **feature engineering**, and **machine learning models**, the analysis shows how property characteristics and location impact sale values.

## Dataset
- **Source:** Ames Housing dataset (Kaggle / open dataset)  
- **Rows:** ~2,930  
- **Columns:** 80+ features, including:
  - Property Details: Lot Area, Overall Quality, Year Built
  - Interior Features: Living Area (SqFt), Basement, Garage
  - Location: Neighborhood, Street, Zoning
  - **Target:** SalePrice

## Dashboard Insights
- **EDA:** Explored relationships between price and features (overall quality, living area, neighborhood).
- **Feature Engineering:** Created combined metrics (e.g., total square footage).
- **Modeling:** Implemented **Linear Regression** and **Random Forest Regressor** for prediction.
- **Explainability:** Used **SHAP** values to interpret how features drive predictions.

## Tools & Techniques
- **Python**
  - pandas, numpy for data manipulation
  - matplotlib, seaborn for visualization
  - scikit-learn for modeling
  - shap for model explainability

## Key Findings
- **Overall quality**, **living area**, and **neighborhood** are the strongest predictors of sale price.
- **Random Forest** achieved higher predictive accuracy than Linear Regression.
- SHAP confirmed that **quality- and size-related features** drive the largest price changes.
