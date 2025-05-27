# Volatility Forecasting for Equity Options on the National Stock Exchange of India
This report applies four return-based volatility estimation methods to 64 stocks from 2010 to 2020, finding that the Root Sum of Squares (RSS) method most accurately tracks realized volatility for short-dated options. Seven forecasting methods were evaluated, including regression, machine learning, and GARCH time series models. Decision trees and random forests significantly outperformed the time series approaches, with momentum factors like historical volatility and total return emerging as the most predictive features. These forecasts were applied to a portfolio trading strategy, but neither model delivered meaningful long-term returns, indicating the need for a more robust approach to consistently outperform the market.

|  | RSS | GARCH |
| --- | --- | --- |
| R<sup>2</sup>  | 0.4598  | -0.0293 |
| MAE  | 0.0612  | 0.1072 |
| RMSE | 0.1016 | 0.1402 |
