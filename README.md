# Daily Sales Forecasting Using Machine Learning

## Project Overview
A machine learning project that forecasts aggregated daily retail sales using a Random Forest Regressor.

## Dataset
Source: [Kaggle Store Sales - Time Series Forecasting](https://www.kaggle.com/competitions/store-sales-time-series-forecasting/data)

The original dataset is not included in this repository.

## Methodology
- Aggregated historical sales by date.
- Created date-based, lagged-sales, and rolling-average features.
- Used a chronological training and testing split.
- Trained a Random Forest regression model.
- Evaluated performance using MAE and RMSE.
- Visualized actual versus predicted sales.

## Results
- MAE: 77,012.06
- RMSE: 120,032.14
- Training rows: 1,336
- Testing rows: 334

## Files
- `sales_prediction.ipynb` — notebook containing code and analysis.
- `sample_predictions.csv` — sample predictions.
- `sales_forecasting_model.joblib` — trained model.

## Technologies
Python, pandas, NumPy, Matplotlib, scikit-learn, joblib, Kaggle, and GitHub.

## Limitations
This is an educational forecasting project, not a production-ready SaaS application. Performance on future data may differ.
