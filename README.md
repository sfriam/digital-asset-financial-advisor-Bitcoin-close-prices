# 💹 Digital Asset Financial Advisor – Bitcoin Close Price Prediction

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow)](https://www.tensorflow.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.x-green?logo=scikitlearn)](https://scikit-learn.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-lightgrey.svg)](LICENSE)

> 📈 An AI-powered pipeline to forecast Bitcoin close prices using market data and investor sentiment indicators.

---

## 🚀 Overview
This project is part of a **Digital Asset Financial Advisor** system. It predicts Bitcoin **closing prices** by combining:
- **Time-series forecasting** (ARIMA)
- **Machine Learning benchmarks** (Linear Regression, Random Forest)
- **Deep Learning** (LSTM networks for sequential data)

It also integrates **investor sentiment analysis** via the **Fear & Greed Index** and other market metrics.

---


---

<details>
<summary>⚙️ Features & Methods</summary>

### 🔹 Data Preprocessing
- Missing value handling
- Lag features for past close prices
- Rolling averages (7h, 24h)
- Sentiment index transformations
- Cyclical time encoding (hour_sin, hour_cos)
- MinMax scaling for LSTM inputs

### 🔹 Models Implemented
1. **ARIMA** – Statistical baseline for time-series.
2. **Linear Regression** – Quick ML benchmark.
3. **Random Forest** – Nonlinear tree-based benchmark.
4. **LSTM** – Deep learning for sequence modeling.

### 🔹 Evaluation Metrics
- **MAE** (Mean Absolute Error)
- **RMSE** (Root Mean Squared Error)
- **R²** (Coefficient of Determination)

</details>

---

## 📊 Model Performance
| Model                  | MAE       | RMSE      | R²       |
|------------------------|-----------|-----------|----------|
| Linear Regression      | 11.91     | 13.94     | 0.9999   |
| Random Forest          | 2548.35   | 5840.41   | 0.3673   |
| LSTM (Reduced Features)| 0.0075    | 0.0118    | 0.9951   |

📌 **Key Insight:**  
The **Reduced Feature LSTM** performed best, indicating that a smaller set of well-engineered features can improve generalization.

---

## 📈 Visuals

### Actual vs Predicted (LSTM)
[LSTM Predictions]

### Correlation Heatmap
[Correlation Matrix]

---

## 🔮 Future Enhancements
- Add **attention mechanisms** for interpretability in LSTM.
- Expand to **multi-crypto forecasting**.
- Deploy as **real-time prediction API** for advisory platforms.

---

## 🛠 Installation
```bash
git clone https://github.com/sfriam/digital-asset-financial-advisor-Bitcoin-close-prices.git
cd digital-asset-financial-advisor-Bitcoin-close-prices
pip install -r requirements.txt

