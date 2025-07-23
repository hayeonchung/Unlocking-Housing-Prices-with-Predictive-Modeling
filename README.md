# From Features to Finance: Unlocking Housing Prices with Predictive Modeling

This project explores the Ames Housing dataset using a variety of machine learning techniques to predict house prices. Through data cleaning, feature engineering, and model tuning, I uncover the key factors that drive housing value and compare the performance of multiple predictive models.

## Project Goals
- Identify the most influential factors affecting housing prices
- Compare model performance between linear regression, random forest, and XGBoost
- Use log transformation to address skewness and improve predictive accuracy
- Communicate insights with interpretable visualizations and metrics

## Methods Used
- Data cleaning & imputation
- Feature engineering
- Linear regression (with multicollinearity handling)
- Random Forest with feature importance analysis
- XGBoost modeling
- RMSE-based model evaluation
- SHAP-style interpretability (via variable importance plots)

## Key Insights
- Home quality, size, and neighborhood are the most significant predictors
- Log transformation of SalePrice improves model performance
- Tree-based models outperform linear regression in capturing complex interactions

## Files
- `housing_modeling.Rmd`: R Markdown notebook with full analysis
- `housing_modeling.pdf`: Knitted PDF with results, plots, and write-up

## Technologies
- R, caret, randomForest, xgboost, tidyverse, ggplot2, knitr

## Dataset
Ames Housing Dataset (originally compiled by Dean De Cock), available via Kaggle or the `AmesHousing` R package.
