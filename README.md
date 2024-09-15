## [Live R Quarto Document](https://sehyunlee217.github.io/fertility_rate_analysis/fertility_rate_analysis.html)
![Screenshot 2024-09-14 at 20 16 25](https://github.com/user-attachments/assets/819d210c-9a10-4959-94e4-9ce4d873d12e)

## Analysis of South Korea's Fertility / Birth Rate 
- Investigating the policy-driven factors contributing to South Korea’s declining birth rate, modeling, and producing scenario-based forecasts.

## Comparative Analysis: Fertility rate trends between South Korea and Japan
**Explanatory Variables**:
- Female employment rates
- Paternal leave policies and proportions by gender
- Child care facility availability and composition

**Multi-Regression Modeling**:
- Multi-linear regression model incorporating parental leave rates and trend components.
- Forecasting future fertility rates based on different policy scenarios.
- Multi-regression model performed better than MA(1) model with 1 differencing; equivalent to ARIMA(0,2,1) for leave-one-out cross validation on all CV criterias(RMSE, MAPE, RMSEE). 

## Main Findings
- South Korea’s birth rate is declining faster than Japan’s, despite similar female employment trends.
- Child Care & Paternal Leave: Higher paternal leave rates and expanded child care in Japan have slowed its birth rate decline.
- Forecast: Based on current trends for paternal leave, fertility rate between 0.41994 and 0.42006 is estimated with 95% confidence intervals for 2030. 
- Proposed Scenario: Increasing maternity leave proportions to 84.5% by 2030 could improve South Korea’s fertility rate by 20%.

## Datasets & Sources 
- [KOSIS](https://kosis.kr/index/index.do)
- [Statistics Bureau of Japan](https://www.stat.go.jp/english/info/news/20240524.html)
- [OECD Data](https://www.oecd.org/en/data.html)
