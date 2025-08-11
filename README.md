Digital Asset Financial Advisor – Bitcoin Close Price Prediction

This project builds a machine learning and deep learning pipeline to predict Bitcoin close prices using historical market data and investor sentiment indicators.
It is part of a broader initiative to develop a digital asset financial advisor, integrating sentiment analysis, market trends, and time-series forecasting.

📌 Project Overview
Goal: Predict short-term Bitcoin closing prices using historical price data, sentiment indices, and other market indicators.

Key Approaches:

ARIMA for statistical time-series forecasting.

Base Machine Learning Models (Linear Regression, Random Forest) for quick benchmarks.

LSTM (Long Short-Term Memory) deep learning model for sequential data patterns.

Data Sources:

Historical Bitcoin price and market metrics.

Investor sentiment indicators (e.g., Fear & Greed Index, sentiment volatility).

Additional social and market dominance metrics.

⚙️ Features
Data Preprocessing:

Missing value handling, feature engineering, lag/rolling averages, and normalization.

Feature Engineering:

Lag features for past closing prices.

Sentiment index transformations.

Time-based cyclical features (hour_sin, hour_cos).

Modeling:

ARIMA for baseline forecasting.

Linear Regression & Random Forest for initial benchmarks.

LSTM for capturing sequential dependencies in Bitcoin price movements.

Evaluation Metrics:

MAE (Mean Absolute Error)

RMSE (Root Mean Squared Error)

R² (Coefficient of Determination)

📊 Visualization
Price trends vs. predictions.

Correlation analysis between sentiment and price.

Actual vs. Predicted plots for model comparison.

💡 Future Enhancements
Incorporate attention mechanisms for feature importance in LSTM.

Expand to multi-cryptocurrency forecasting.

Deploy as a real-time prediction API for digital asset advisory.

