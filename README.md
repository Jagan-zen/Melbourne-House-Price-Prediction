# Melbourne House Price Prediction 🏠📊

## Overview
This project predicts house prices in Melbourne using machine learning models.
Random Forest and XGBoost were evaluated, with XGBoost achieving the best performance.

## Dataset
- Source: Kaggle – Melbourne Housing Snapshot
- Target Variable: Price

## Features Used
Rooms, Bathroom, BuildingArea, Type, YearBuilt, Suburb, Distance, Landsize

## Models
- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

## Results
| Model | MAE | RMSE | R² |
|------|-----|------|----|
| Random Forest | ~156k | ~226k | ~0.76 |
| XGBoost (untuned) | **135k** | **197k** | **0.82** |

## Conclusion
XGBoost outperformed Random Forest even without hyperparameter tuning, demonstrating
strong predictive performance on tabular housing data.

## Future Work
- Hyperparameter tuning
- Feature engineering
- Model deployment
