# Project 06 — Demand Forecasting (Daily Delivery Volume)

## 1. Executive Context
This project simulates a real-world logistics scenario where the company needs to improve its ability to predict daily delivery demand. Current estimations rely on simple averages and manual rules, which fail to capture temporal patterns such as trend, seasonality, holidays, and operational fluctuations.

The Applied AI & Operations division requested the development of a forecasting prototype based on historical daily delivery volume.

---

## 2. Preliminary Problem Identification (PPI)
*Based on the IA/ML Decision Framework – Jairo Costa*

- **Objective:** Forecast the daily delivery volume (time series regression)
- **Data Type:** Time series (daily)
- **Labels Available:** Yes (historical volume)
- **Problem Category:** Time Series Forecasting
- **Candidate Approaches:**
  - Statistical baselines (Naive, Moving Average, Drift)
  - ARIMA/SARIMA (optional)
  - Machine Learning with engineered temporal features
  - Prophet or similar additive models

A full PPI analysis will be documented inside the study notebook before any modeling begins.

---

## 3. Deliverables
- Study notebook (with reasoning, errors, questions, attempts)
- Final notebook (clean and documented)
- EDA: trend, seasonality, autocorrelation
- Forecasting models and comparison (MAE, RMSE, MAPE)
- Business interpretation of results
- Artifacts: plots, metrics, model insights

---

## 4. Repository Structure
```
project-06-demand-forecasting/
├── README.md
├── data/
├── artifacts/
├── notebooks/
│   ├── study-version.ipynb
│   └── final-version.ipynb
└── requirements.txt
```

---

## 5. Notes
This project follows a guided autonomy approach: decisions are taken by the author, validated by a mentor, and refined throughout the study notebook.

