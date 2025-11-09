# Electricity Consumption – France (EDA & Forecast)

This project analyzes electricity consumption in France and explores simple forecasting baselines.

## Objectives
- Clean and explore electricity consumption data.
- Visualize trends (daily/weekly/seasonal effects).
- Try a simple baseline forecast (e.g., moving average / ARIMA / Prophet).

## Data
- `cons_elec_france.csv` — dataset (briefly document columns & source if public).
- `electricitydatavafa.ipynb` — main analysis notebook.

## Environment
```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter lab
