# Netflix Stock Price Prediction

## 📌 Overview
This project focuses on forecasting Netflix (NFLX) daily closing stock prices using advanced Time-Series Analysis. By analyzing historical financial data, the model aims to provide accurate short-term price predictions to aid investment decision-making.

## Methodology & Features
* **Data Preprocessing:** Handled non-stationary data using **Box-Cox Transformation** and **Differencing** (validated via ADF Test).
* **Modeling:** Implemented **ARIMA(1,1,0)** algorithm.
* **Optimization:** Utilized **Grid Search** for automated hyperparameter tuning.
* **Validation:** Applied **Rolling Forecast (Walk-Forward Validation)** strategy to simulate real-world trading scenarios.

## Results
The model achieved high accuracy with the following metrics:
* **MAPE (Mean Absolute Percentage Error):** **1.53%** 🚀

![Graph Prediction](https://drive.google.com/file/d/1kdhu2vhs7TgS0-9Hs9kgvW7MeGw15FnL/view?usp=sharing)
*(Figure: Comparison between Actual Price vs Predicted Price)*

## Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Statsmodels, Scikit-learn.

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone [https://github.com/username/netflix-forecasting.git](https://github.com/username/netflix-forecasting.git)
