# Module 8: Correlating search trends and stock prices

## Project Overview
This project analyzes Google Search Trends for MercadoLibre and explores their relationship with stock price patterns. The study applies time series analysis using Facebook's Prophet forecasting model to identify seasonal patterns and predict future search interest.

## Key Objectives
- **Find unusual patterns in search traffic**
  - Analyze hourly search trends and detect anomalies.
  - Compare monthly search volume against historical medians.
  - Identify if search traffic increased during financial result releases.

- **Analyze search traffic seasonality**
  - Investigate search trends by hour of the day.
  - Compare search volume by day of the week.
  - Detect seasonal trends by week of the year.

- **Relate search trends to MercadoLibre stock prices**
  - Merge stock closing prices with search trends.
  - Compute lagged search trends and stock volatility.
  - Explore potential correlations between search traffic and stock movements.

- **Time Series Forecasting with Prophet**
  - Train a Prophet model to forecast future search trends.
  - Analyze daily, weekly, and yearly seasonality.
  - Answer key questions about time-based search trends.

## Tools & Libraries
- Python
- Pandas, NumPy for data manipulation
- Matplotlib, Seaborn for data visualization
- Facebook Prophet for time-series forecasting
- Scikit-learn for data normalization

## Key Findings
- Peak search interest occurs at midnight GMT (5-6pm local) of the day.
- Most search traffic happens on Tuesday.
- Search trends exhibit a seasonal dip in late October and Christmas holidays.
- Stock volatility shows weak correlation with search trends (-0.1 correlation).
- Prophet forecasting predicts stability in search trends.


## Future Enhancements
- Improve model accuracy with additional features (e.g., economic indicators).
- Experiment with different forecasting models.
- Extend analysis to other e-commerce companies.


**Author:** Jill Balderson


## License
This project is open-source under the [MIT License](LICENSE).

