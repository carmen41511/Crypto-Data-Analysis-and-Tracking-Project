# Cryptocurrency Market Data Analysis and Tracking Project

## Install

Simply install the python package:
```shell
pip install -r requirements.txt
```

## Dataset

This dataset contains historical cryptocurrency price data sourced from [Binance](https://www.cryptodatadownload.com/data/binance/). Binance is a cryptocurrency exchange that was founded in 2017. It is one of the largest cryptocurrency exchanges in the world, with a daily trading volume of over $2 billion.

The data is in CSV format and includes the following columns after data processing:

- Unix Timestamp - This is the unix timestamp or also known as "Epoch Time". Use this to convert to your local timezone
- Date - This timestamp is in UTC datetime
- Symbol - The symbol for which the timeseries data refers
- Open - This is the opening price of the time period
- High - This is the highest price of the time period
- Low - This is the lowest price of the time period
- Close - This is the closing price of the time period
- Volume (Crypto) - This is the volume in the transacted Ccy. Ie. For BTC/USDT, this is in BTC amount
- Volume Base Ccy - This is the volume in the base/converted ccy. Ie. For BTC/USDT, this is in USDT amount
- Trade Count - This is the unique number of trades for the given time period

The data covers the period from July 1, 2019 to May 15, 2023.
