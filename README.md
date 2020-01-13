# UMD SIF Notebooks

A small collection of notebooks I made at University of Maryland's Smith Investment Fund

<p align="center">
  <img src="https://github.com/arda-arslan/umdsif/blob/master/assets/backtester_img.png" width="95%" />
</p>

## Notebooks

1. Backtester: Backtesting a research idea and calculating it's performance metrics are important steps in seeing whether an idea holds water. This backtester calculates the daily performance metrics (net of transaction costs) of a long-only strategy, as well as the corresponding rolling sharpe and sortino ratios.
2. Intro to Quantitative Research: Everybody starts somewhere. This notebook is meant to be a light introduction to Quantopian's research platform.
3. Easy Betas and Other Factors: I had some difficulty finding an easy way to calculate betas, so I created this notebook to walk myself through that process.
4. Stationarity Research: Stationarity means that the statistical properties of a time series don't change over time. This is meaningful because if we can find a stationary signal, it could have the potential to be used as an investment strategy. This notebook explores whether equity returns could be stationary.

## Requirements
- Jupyter
- matplotlib
- numpy
- pandas
- seaborn
- statsmodels
