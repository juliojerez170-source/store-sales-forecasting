# Store Sales Forecasting

Forecast daily unit sales at the store × product family level.  
Focus: strong baselines, time-series backtesting (no leakage), feature engineering and interpretable ML.

## Project plan
- Data QA + EDA
- Feature engineering (calendar, lags, rolling stats, promotions)
- Baselines: naive / seasonal naive
- Model: gradient boosting (e.g., LightGBM)
- Evaluation: rolling-origin backtesting

## Repo structure
- `data/`: data instructions (raw data not tracked)
- `notebooks/`: 00 setup, 01 EDA, 02 features, 03 modeling, 04 results
- `src/`: reusable code
- `reports/`: figures + final write-up