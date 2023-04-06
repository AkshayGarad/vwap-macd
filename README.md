# VWAP MACD Indicator for TradingView
This repository contains a Pine Script code for the VWAP MACD indicator on TradingView. The VWAP MACD combines the Moving Average Convergence Divergence (MACD) and the Volume Weighted Average Price (VWAP) indicators.

## How to Use
- Copy the code from the `vwap_macd.pine` file.
- Open TradingView and go to the Pine Editor.
- Paste the code into a new script and save it.
- Apply the script to any chart.

You can adjust the settings for the MACD length and source using the "Inputs" tab on the Study Settings panel.

## Indicator Calculation
The VWAP is calculated as the ratio of the sum of volume times close to the sum of volume. The MACD is calculated as the difference between the 12-period exponential moving average (EMA) and the 26-period EMA of the selected source (default is hlc3). The signal line is calculated as the 9-period EMA of the MACD. The VWAP MACD is then calculated as the difference between the MACD and the VWAP.

## Plotting
The indicator plots the MACD, the signal line, and the VWAP MACD. It also includes a zero line and alerts for bullish and bearish crosses of the MACD and its signal line.

## Disclaimer
This code is provided for educational and informational purposes only and should not be considered financial advice. Always conduct your own research and make informed decisions when trading.