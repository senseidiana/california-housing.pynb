# California Housing Price Prediction

## Objective
Build and evaluate a machine learning model to predict median house prices
using the California Housing dataset.

## Dataset
Source: scikit-learn California Housing dataset

Target variable:
- MedHouseVal

Features:
- MedInc
- HouseAge
- AveRooms
- AveBedrms
- Population
- AveOccup
- Latitude
- Longitude

## Methodology
- Data split: 80% train / 20% test
- Baseline model: Linear Regression
- Improved model: RandomForestRegressor
- Pipeline with preprocessing (StandardScaler)
- Evaluation metrics: MAE and R²

## Results
- Linear Regression: MAE ≈ 0.53, R² ≈ 0.58
- Random Forest: MAE ≈ 0.33, R² ≈ 0.81

## Conclusion
The RandomForest model significantly improved performance by capturing
non-linear relationships. The results are consistent with real estate
pricing dynamics.
