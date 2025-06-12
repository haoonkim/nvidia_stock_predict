# NVIDIA Stock Price Analysis & Prediction

This project explores and predicts NVIDIA's stock price using historical data from Yahoo Finance. The analysis includes data cleaning, visualization, correlation analysis, and machine learning (Random Forest) for price prediction.

## Project Objectives

- Collect historical NVDA stock data using `yfinance`
- Clean and preprocess data
- Visualize stock trends, volatility, and patterns
- Use Random Forest Regression to predict stock closing prices
- Predict short-term future prices (30 days)
- Evaluate model accuracy using Mean Squared Error (MSE)

---

## Project Structure
- nvda_analysis.ipynb # Full exploratory analysis + modeling
─ future_predictions.png # Visualization of future prices (output)
─ plots/ # Contains generated plots
─ README.md # Project overview (this file)

## Tools & Libraries

- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `plotly`, `chart_studio`
- `yfinance` (data source)
- `sklearn` (for RandomForest model)

## Highlights

- Data from 1999–2024** (6400+ daily records)
- Correlation Heatmap** of OHLC/Volume features
- Log-scaling** to reveal long-term trends
- Random Forest** used to predict closing prices
- 30-Day Future Prediction visualization

##ouput
-Mean Squared Error** (Test Set): `~0.076` 

 ## Insights

- Strong correlation between `Open`, `High`, `Low`, and `Close` prices.
- Volume varies drastically over the years but has less correlation with price.
- The model performs reasonably well on recent historical data and can suggest directional trends.
