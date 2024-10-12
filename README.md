# 🏆 Gold Price Prediction

Welcome to the **Gold Price Prediction** project! This repository contains a machine learning model that predicts gold prices using various market factors such as stock indices, oil prices, silver prices, and currency exchange rates. Gold price prediction is crucial for financial analysts, investors, and traders who want to anticipate future market trends.

## 📄 Project Overview

The goal of this project is to build a predictive model that accurately forecasts the price of gold based on other financial indicators. We use machine learning techniques, specifically the **RandomForestRegressor**, to model the relationship between features such as SPX, USO, SLV, and EUR/USD with gold prices.

### 🌟 Key Features

- **Data Analysis**: Exploratory Data Analysis (EDA) on gold price data and related financial factors.
- **Random Forest Regressor**: A powerful ensemble model to predict gold prices.
- **Visualization**: Various plots to visualize the distribution of data and model performance.
- **Performance Metrics**: Evaluation of the model using R-squared and Mean Absolute Error (MAE).

## 📂 Dataset

The dataset used in this project can be found on [Kaggle](https://www.kaggle.com/datasets/altruistdelhite04/gold-price-data).

**Columns in the dataset**:
- `Date`: The date of the record.
- `SPX`: S&P 500 Index.
- `GLD`: Gold Price (our target variable).
- `USO`: Crude Oil Prices.
- `SLV`: Silver Prices.
- `EUR/USD`: Euro to US Dollar exchange rate.

## 📊 Exploratory Data Analysis (EDA)

- We explore the distribution of gold prices and the correlation between features.
- A **heatmap** is used to visualize correlations between variables, identifying which features are most impactful in predicting gold prices.

## 🚀 Model Training and Evaluation

- **Model**: We used the **RandomForestRegressor** to build our predictive model.
- **Train-Test Split**: The data was split into 80% training and 20% testing sets.
- **Performance Metrics**: The model was evaluated using the R-squared score and Mean Absolute Error (MAE). The model achieved an R-squared score of **0.98**, showing high accuracy in predicting gold prices.

## 📈 Visualization

- **Actual vs Predicted Prices**: We plotted the actual vs predicted gold prices to visualize the model's performance.

## 💡 Observations

- Gold price is positively correlated with the EUR/USD exchange rate and negatively correlated with the S&P 500 index (SPX).
- The **RandomForestRegressor** effectively captured the trend of gold prices with a high level of accuracy.

## 🛠️ Tech Stack

- **Python** 🐍
- **Pandas** for data manipulation
- **Seaborn** and **Matplotlib** for data visualization
- **Scikit-learn** for machine learning model
- **RandomForestRegressor** for regression modeling

## 📬 Get in Touch

- **Author**: [Syed Muhammad Ebad](https://www.kaggle.com/syedmuhammadebad)
- [Send me an email](mailto:mohammadebad1@hotmail.com)
- [GitHub Profile](https://github.com/smebad)

## 📝 Conclusion

This project successfully predicts gold prices using a **RandomForestRegressor** model with high accuracy. Further improvements could be achieved by trying other advanced models like **XGBoost** or including additional macroeconomic features for better prediction.

If you found this project helpful, feel free to give it a ⭐ on GitHub or suggest improvements!

---

Happy coding! 💻
