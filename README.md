# 📈 Netflix Stock Price Prediction

![Python](https://img.shields.io/badge/Python-3.9-blue) ![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Overview
This project focuses on forecasting Netflix (NFLX) daily closing stock prices using advanced Time-Series Analysis. By analyzing historical financial data, the model aims to provide accurate short-term price predictions to aid investment decision-making.

## 🛠 Methodology & Features
* **Data Preprocessing:** Handled non-stationary data using **Box-Cox Transformation** and **Differencing** (validated via ADF Test).
* **Modeling:** Implemented **ARIMA(1,1,0)** algorithm.
* **Optimization:** Utilized **Grid Search** for automated hyperparameter tuning.
* **Validation:** Applied **Rolling Forecast (Walk-Forward Validation)** strategy to simulate real-world trading scenarios.

## 📊 Results
The model achieved high accuracy with the following metrics:
* **MAPE (Mean Absolute Percentage Error):** **1.53%** 🚀
* **RMSE:** [Masukkan angka RMSE jika ada]

![Graph Prediction](link-ke-gambar-grafik-kamu.png)
*(Figure: Comparison between Actual Price vs Predicted Price)*

## 💻 Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Statsmodels, Scikit-learn.

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone [https://github.com/username/netflix-forecasting.git](https://github.com/username/netflix-forecasting.git)
