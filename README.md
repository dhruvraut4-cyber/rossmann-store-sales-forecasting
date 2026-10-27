# Rossmann Store Sales Forecasting & Sales Driver Analysis

## Project Overview
This project analyzes historical sales data from Rossmann stores and builds a machine learning model to forecast daily sales. It explores weekly patterns, promotions, store characteristics, and historical sales trends.

## Objectives
- Explore historical store sales and identify patterns.
- Analyze sales across weekdays and promotion periods.
- Engineer calendar and historical sales features.
- Train an XGBoost regression model.
- Compare XGBoost against a seasonal baseline.

## Dataset
The project uses the Rossmann Store Sales dataset from Kaggle.

Dataset source: https://www.kaggle.com/competitions/rossmann-store-sales

The dataset includes historical sales records, store characteristics, and competition test data.

## Methodology
1. Data cleaning and exploratory data analysis.
2. Feature engineering for dates and historical sales.
3. Chronological training and validation split.
4. XGBoost model training.
5. Evaluation using MAE and RMSE.
6. Feature importance and prediction error analysis.

## Models
- Seasonal baseline: previous week's sales for the same store.
- XGBoost regression: uses calendar, store, promotion, and historical sales features.

## Results
Final validation metrics will be added after the corrected model and baseline comparison have been verified.

## Tools & Technologies
Python, pandas, NumPy, Matplotlib, scikit-learn, XGBoost, Jupyter Notebook.

## Limitations
- Validation represents rolling one-day-ahead forecasting, assuming recent actual sales are available.
- Feature importance does not establish causation.
- This project forecasts sales; it does not directly predict inventory or stockouts.

## Author
Dhruv Raut

GitHub: https://github.com/dhruvraut4-cyber
