# Hybrid AQI Prediction Model

Hybrid air quality forecasting pipeline using time-series modeling plus machine learning explainability:

- SARIMA for seasonality and temporal structure
- XGBoost for nonlinear feature learning
- SHAP for model interpretation

Main project notebook: `code-v_1-0-0.ipynb`

## Project Pipeline

1. Data preprocessing and feature engineering
2. SARIMA baseline modeling
3. Feature fusion (SARIMA outputs + engineered predictors)
4. XGBoost training and evaluation
5. SHAP explainability analysis

## Requirements

- Python 3.9+
- See `requirements.txt`

Install dependencies:

```bash
pip install -r requirements.txt
```

## Data

The notebook references the dataset path:

`../aqi_era5_daily_2015_2019_clean.csv`

Place the dataset accordingly, or update the path in the notebook.

## Run

Open and run:

`code-v_1-0-0.ipynb`

Use Jupyter Notebook, JupyterLab, or VS Code notebooks.

## Evaluation Metrics

- MAE
- RMSE
- MAPE

## Repository Structure

```text
.
|-- code-v_1-0-0.ipynb
|-- requirements.txt
|-- .gitignore
`-- README.md
```

## License

Add a license file before public release if required by your project policy.
