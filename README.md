# Poorman's Options Lab
---

## TL;DR

This notebook has thrree tools
1. find_best_put_to_sell
  - input a ticker and the max breakeven price, output the top cash covered put options to sell that yields highest Annualized Return Rate for the cash collateral. 
2. find_best_call_to_sell
  - input a ticker and the min breakeven price, output the top covered call options to sell that yields highest Annualized Return Rate for the equity collateral.
3. find_best_call_to_buy
  - input a ticker, visualize the Implied Volatility of call option over different expiration dates and strike prices. The dips in the curves are **probably** better choices to buy than their neighbors.

## Disclaimer

This software comes with absolutely no warranty nor support whatsoever, and it's purely for research purpose. Use it at your own risk.

## FAQ

1. How to use this notebook? 
  - Search "how to use ipython notebook". 
  - Run "Common Block" first, then run the individual tools block.
2. Where did you get the data? 
  - All the financial data used by this program are from yahoo finance. 
  - The data quality (accuracy, integrity, latency, etc.) is totally up to [finance.yahoo.com](https://finance.yahoo.com/) and the [yfinance](https://pypi.org/project/yfinance/) tool.
3. Suggestions? Discussions? 
  - Create issues in the GitHub project: [Options Lab](https://github.com/fanzhenya/options_lab/blob/main/options_lab.ipynb)
