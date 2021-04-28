## BTC/USD and ETH/BTC 1-day Charts
This project has two components:
1. BTC/USD Candlestick charts
    1. a. Coinbase platform
    1. b. Gemini platform
2. ETH/BTC notional volume in USD on Coinbase

## Files
* **jupyter_version-1.ipynb​**: python script for retrieving, cleaning, and visualizing data
* **jupyter_version-1.pdf**: jupyter notebook exported as pdf
* **jupyter_version-1.html**: jupyter notebook exported as html
* /graphs
    * **BTCUSD - Coinbase**: Hourly candlesticks for BTC/USD on Coinbase
    * **BTCUSD - Gemini**: Hourly candlesticks for BTC/USD on Gemini
    * **ETHBTC_vol - Coinbase**: Hourly notional volume (USD) for ETH/BTC on Coinbase
* 

## API Referenced
- [Coinbase](https://docs.pro.coinbase.com/)
    - [Get Trades](https://docs.pro.coinbase.com/#get-trades)
    - [Get Historic Rates](https://docs.pro.coinbase.com/#get-historic-rates)
- [Gemini](https://docs.gemini.com/)
    - [Trade History](https://docs.gemini.com/rest-api/#trade-history)

## Tech/framework used

<b>Built with</b>
- Python3 
- Jupyter Notebook
- Pandas


## Installation
- Run each cell in Jupyter Notebook sequentially to reproduce the graphs in the first component.
- Running task 2 cells would result in a different graph than the one in name.pdf because it would produce a notional volume graph from the current time window--1 day from the total time. 
 


