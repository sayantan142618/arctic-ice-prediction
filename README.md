# 🧊 Arctic Ice Prediction Project – Time Series Forecasting with ARIMA

This repository contains two versions of a project that forecasts monthly Arctic sea ice extent using time series modeling with ARIMA. It includes a **simulated dataset version** for concept demonstration and a **real dataset version** that works with `.csv` files containing monthly sea ice data.

---

## 📁 Contents

| File                                 | Description                                              |
|--------------------------------------|----------------------------------------------------------|
| `Arctic Ice Prediction with simulated datasheet.ipynb.ipynb` | Forecast using a **simulated dataset** (2010–2024)       |
| `Arctic_Ice_Prediction With Real datasheet.ipynb.ipynb`     | Forecast using a **real monthly CSV dataset**            |
| `ice_data.csv`                         | Sample CSV file used in the real-data notebook           |
---

## 🧠 Project Objectives

- Demonstrate time series forecasting using ARIMA
- Visualize climate-related trends in Arctic sea ice extent
- Create a flexible solution for both synthetic and real-world datasets
- Deliver resume-ready, interview-friendly climate ML project

---

## 🧪 Notebook 1: Simulated Dataset Version

**File**: `Arctic_Ice_Prediction_Complete.ipynb`

- Creates synthetic daily Arctic ice extent data (2010–2024)
- Resamples into monthly averages
- Applies ARIMA(5,1,2) for forecasting next 12 months
- Visualizes observed vs. forecasted data

📌 *Useful for interview demos and model understanding*

---

## 📁 Notebook 2: Real Dataset Version

**File**: `Arctic_Ice_Prediction_REAL.ipynb`  
**Input CSV**: `ice_data.csv`

- Accepts any CSV file with:
  - `Date` column (monthly, e.g., `2012-01-01`)
  - `Extent` column (numeric, e.g., `9.75`)
- Cleans and processes data
- Applies ARIMA(5,1,2) and generates future forecast
- Uses `freq='ME'` (Month End) to avoid deprecation issues
- Suppresses all warnings for clean output

📌 *Ready to plug into real-world Arctic or climate datasets*

---

## 📊 Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Statsmodels (ARIMA)
- Jupyter Notebook

---

## 📈 Outputs
- Line chart of observed Arctic ice trends
- Forecast for next 12 months
- Highlight of seasonal patterns and long-term decline

---


