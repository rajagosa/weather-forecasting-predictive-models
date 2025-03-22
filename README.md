# weather-forecasting-predictive-models
Forecasted global temperatures using Facebook Prophet and XGBoost. Cleaned and analyzed 60k+ rows of weather data, detected outliers, and evaluated models with MAE.
# 🌦️ Weather Forecasting with Machine Learning

This project forecasts global temperatures using **Facebook Prophet** for time-series modeling and **XGBoost** for machine learning regression. Over **60,000+ rows of global weather data** were cleaned, analyzed, and modeled to predict temperature trends with high accuracy.

---

## 📌 Project Highlights

- Cleaned and processed a large weather dataset
- Engineered time-based features (year, month, day, hour, weekday)
- Built and compared two predictive models:
  - **Prophet** for time-series forecasting
  - **XGBoost Regressor** using custom features
- Evaluated both models using **Mean Absolute Error (MAE)**

---

## 📊 Results

| Model   | MAE (Mean Absolute Error) |
|---------|---------------------------|
| Prophet | 2.21                      |
| XGBoost | 2.64                      |

> ✅ **Prophet slightly outperformed XGBoost** in capturing seasonality and temperature trends in this dataset.

---