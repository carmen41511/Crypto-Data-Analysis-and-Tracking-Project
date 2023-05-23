# Cryptocurrency Market Data Analysis and Tracking Project

Welcome to my personal project that aims at analyzing and tracking the cryptocurrency market. The goal is to collect and clean market data to calculate useful metrics for analyzing key cryptocurrencies. I intend to build an interactive plotly dashboard that provides insights through visualizing key metrics on different charts. Users will be able to filter data by date ranges and cryptocurrencies. So far I have processed the necessary data and next steps include designing the dashboard layout, adding the filtering components and charts. Ultimately, my vision is to create an actionable cryptocurrency tracking dashboard that provides valuable insights through intuitive data visualization.

## Install

Simply install the python package:
```shell
pip install -r requirements.txt
```

## Dataset

This dataset contains historical cryptocurrency price data sourced from [Binance](https://www.cryptodatadownload.com/data/binance/). Binance is a cryptocurrency exchange that was founded in 2017. It is one of the largest cryptocurrency exchanges in the world, with a daily trading volume of over $2 billion.

The data is in CSV format and includes the following columns after data processing:

- Date - This timestamp is in UTC datetime
- Symbol - The symbol for which the timeseries data refers
- High - This is the highest price of the time period
- Low - This is the lowest price of the time period
- Close - This is the closing price of the time period
- Volume USDT - This is the volume in the transacted Ccy. Ie. For BTC/USDT, this is in USDT amount
- Tradecount - This is the unique number of trades for the given time period
- MA50: 50-day simple moving average of closing price.
- MA20: 20-day simple moving average of closing price.
- STD20: 20-day standard deviation of closing price.
- BOLU: Upper band of Bollinger Band, calculated by adding 2 standard deviations to moving average.
- BOLD: Lower band of Bollinger Band, calculated by subtracting 2 standard deviations from moving average.
- RSI: Momentum indicator that measures magnitude of recent price changes to evaluate overbought and oversold conditions.

The data covers the period from January 1, 2021 to present (data updated daily).

![crypto-dataframe](https://github.com/carmen41511/Crypto-Data-Analysis-and-Tracking-Project/assets/53323902/d5b89b53-c78e-4b95-ba41-7926d9bd0a6e)



