📈 Stock Market Analysis & Forecasting (India, 2019–2024):

🧠 Project Overview:
This data science project analyzes historical stock prices of major Indian blue-chip companies. It combines exploratory data analysis, trend visualization, volatility and correlation assessment, and time-series forecasting using Prophet. Designed to be both insightful and technically robust, this notebook demonstrates how Python can be used to extract market intelligence from real-world financial data.

🔍 Features:
- ✅ Historical data extraction using `yfinance`
- 📊 Trend visualizations with `matplotlib`, `seaborn`, and `plotly`
- 📈 Growth comparison via normalized performance
- 📉 Volatility analysis with standard deviation of returns
- 🔗 Correlation heatmap across multiple stocks
- 🔮 Time-series forecasting using Facebook Prophet
- 📎 Interactive charts for dynamic exploration


🛠️ Technologies Used:

| Tool / Library     | Purpose                          |
|--------------------|----------------------------------|
| `yfinance`         | Stock data download              |
| `pandas` / `numpy` | Data manipulation & analysis     |
| `matplotlib` / `seaborn` | Static visualizations      |
| `plotly`           | Interactive plots                |
| `Prophet`          | Forecasting stock prices         |


📁 Dataset:

Daily stock prices for:
- RELIANCE  
- INFY  
- HDFCBANK  
- TCS  
- ICICIBANK  
- HINDUNILVR  
- SBIN  
- BAJFINANCE  
- WIPRO  

Source: [Yahoo Finance](https://finance.yahoo.com/)


🚀 How to Run:

1. Clone or download the repository.
2. Open the notebook using Jupyter or Google Colab.
3. Run the first cell to install dependencies.
4. Execute each cell sequentially to explore insights and generate forecasts.


Stuffs to install: yfinance, prophet, seaborn, plotly.


💡Insights:
- Reliance & Bajaj Finance showed strong upward trends.
- Banking stocks (HDFC, ICICI, SBIN) displayed higher volatility.
- Prophet forecasts project a stable trend for Reliance, with mild seasonality.
- Correlations across banking and IT stocks suggest sector-linked behavior.


⚠️Limitations:
- Forecasts are based only on historical price patterns.
- Macroeconomic factors, news sentiment, and global events aren't modeled.

---

Future Enhancements:
- Streamlit dashboard for interactivity
- Real-time data updates using scheduled jobs
- Integration with sentiment analysis from financial headlines


🙌Credits:
- [Yahoo Finance](https://finance.yahoo.com/) for stock data  
- [Facebook Prophet](https://facebook.github.io/prophet/) for forecasting  
- Open-source Python ecosystem
