# Module 8: Correlating search trends and stock prices

## Overview
This project analyzes MercadoLibre's Google search traffic data and stock price patterns to identify relationships and forecast future trends. As Latin America's most popular e-commerce site with over 200 million users, understanding MercadoLibre's financial and user data patterns can provide valuable insights for growth strategies and potential stock trading opportunities.

## Project Structure
The analysis is divided into four main components:

1. **Finding unusual patterns in hourly Google search traffic**
2. **Mining search traffic data for seasonality**
3. **Relating search traffic to stock price patterns**
4. **Creating a time series model with Prophet**

## Technologies Used
- Python
- Pandas
- Matplotlib
- Prophet
- Numpy

## Data Sources
- Google hourly search trends for MercadoLibre
- MercadoLibre stock price data

## Analysis Details

### 1. Unusual Patterns in Search Traffic
- Analyzed search traffic data during key financial events (May 2020)
- Compared traffic during these periods to median monthly traffic
- Identified whether financial releases correlated with increased search interest

### 2. Search Traffic Seasonality
- Analyzed hourly, daily, and weekly search traffic patterns
- Identified peak hours of search activity
- Determined which days of the week showed highest user interest
- Examined seasonal trends, particularly around winter holiday periods (weeks 40-52)

### 3. Search Traffic and Stock Price Relationship
- Combined search trends with stock price data
- Focused on first half of 2020 to observe COVID-19 impact
- Created metrics including:
  - Lagged Search Trends (offset by one hour)
  - Stock Volatility (exponentially weighted four-hour rolling average)
  - Hourly Stock Return (percent change of stock price hourly)
- Analyzed correlations between search trends and stock metrics

### 4. Time Series Forecasting
- Implemented Prophet model on search traffic data
- Generated search trend forecasts
- Decomposed time series into component parts (trend, seasonality)
- Determined optimal times for marketing based on user search patterns

## Key Findings

### Search Traffic Patterns
- May 2020 (earnings release) showed higher search traffic compared to the median
- Search traffic patternsshowed distinct hourly, daily and seasonal patterns

### Seasonality Insights
- Highest search traffic occurs during 00:00am GMT (17:00-19:00 Local time)
- Tuesday consistently has the highest search volume
- During the year, highest search volume is January and late June, with another spike in December (Holidays)

### Stock and Search Relationships
- The lagged search trend showed weak correlation with stock volatility
- Based on the correlation analysis, there does not appear to be a strong predictable relationship between lagged search traffic and either stock volatility or hourly stock returns.

### Future Forecast
- Near-term forecast for MercadoLibre's popularity shows a slight downward trend

## Conclusion
This analysis demonstrates the value of combining search trend data with financial metrics to understand user interest patterns and their potential relationship with stock performance. The insights gained can help inform marketing strategies and potentially provide signals for stock trading opportunities.

## Instructions for Use
1. Clone this repository
2. Ensure you have the required packages installed:
   ```
   pip install pandas numpy matplotlib prophet
   ```
3. Run the Jupyter notebook to see the complete analysis

## Future Work
- Incorporate additional data sources (e.g., social media mentions)
- Explore more advanced forecasting techniques
- Develop trading strategies based on search-stock relationships
- Expand analysis to include competitor data


**Author:** Jill Balderson


## License
This project is open-source under the [MIT License](LICENSE).

