
# Financial Time Series Forecasting with Risk Assessment

This project builds and compares deep learning models — LSTM, GRU, and a custom 
Transformer-based architecture — to forecast Dow Jones Industrial Average (DJI) 
closing prices using 5 years of historical market data (2018–2023).

Beyond simple price prediction, the project incorporates financial risk metrics 
such as Value at Risk (VaR) to quantify potential downside risk, and explores 
uncertainty estimation techniques (e.g., Monte Carlo Dropout) to move beyond 
single-point forecasts toward probabilistic predictions — similar to approaches 
used in quantitative finance and algorithmic trading research.

The dataset includes daily OHLCV (Open, High, Low, Close, Volume) data, from 
which 18+ technical indicators were engineered — including returns, volatility, 
momentum (RSI, MACD, Stochastic), and trend indicators (moving averages, 
Bollinger Bands) — to give the models richer signal beyond raw prices.
