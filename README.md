# Volatility-Modeling-Bayesian-Approach

### Code/Notebook:
https://github.com/CaptaiNemo4/Volatility-Modeling-Bayesian-Approach/blob/main/Volatility_modeling_bayes.ipynb
### Presentation/Report: 
https://github.com/CaptaiNemo4/Volatility-Modeling-Bayesian-Approach/blob/main/Bayesian_Volatility_modeling_pres.pdf

In this project, we will delve into one of the applications of Bayesian Statistics within Finance, particulraly in volatility modeling.

Volatility measures the degree of variation in the price of financial instruments over time. It reflects the pace and magnitude of price fluctuations.

Why it matters:
- Risk Management: Volatility helps investors gauge the potential risk associated with a financial asset.
- Market Conditions: High volatility may indicate uncertain market conditions, while low volatility suggests stability.
- Investment Strategies: Traders often adjust their strategies based on the level of volatility in the market.
- Volatility Trading: Exploit discrepancies between forecasted volatility and implied volatility. If forecasted volatility is significantly different from implied volatility, it may create arbitrage opportunities.
- Option Pricing: Volatility is a key input in options pricing models like the Black-Scholes Model.

Volatility modeling is crucial for assessing and managing financial risk.

We aim to apply Bayesian Inference in estimating parameters of two well-renowned volatility modeling equations: GARCH (1, 1) and Stochastic Volatility for forecasting the weekly volatility of the S&P 500.

First, we train and fit the models on the historical data from 2013-2018. Next, we assess their performance on the 2019-now, 11.12.2023 period. The backtesting period includes low volatility events as wells as the covid crisis, representing a broader set of possibilities in financial markets. Hence, we believe that backtesting can provide some insights on strenghts and shortcomings of each model when handling various market conditions.
