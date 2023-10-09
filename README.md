
# S&P Sector ETF Anomaly Detection with Isolation Forest - MSc Dissertation Project

## Abstract

This project compares financial performance metrics for holding US Sector Exchange-Traded-Funds (ETFs) after detecting real-time anomalies using the Isolation Forest algorithm over the period 2012-2022. A combination of fundamental and technical data is used to construct the feature set. On average, in most sectors, returns, volatility and risk-adjusted returns all increased following the detection of an anomaly.

## Objectives

- Do Anomalies occur at interesting moments in price?
- What are the returns after anomlaies compared to regular calendar periods? 1-year, 6-months and 3-months are tested.
- What is the volatility of returns over the same time frames?
- What are the risk-adjusted returns over the same time frames?
- What are the implications for investors?

## Project Outline

- Data import & cleaning
- Preprocessing & Feature Engineering
- Data Exploration
- Model Building & Execution
- Results

## Results

- A lot but not all anomalies occur at interesting points.
- Most returns increased following an anomaly.
- Volatility usually following an anomaly.
- Risk-adjusted returns mostly increased across all sectors in the time frames analysed.

## Implications

- May be used to aid timing investments.
- Use to increase market awareness.
- Adapt the model for different asset classes or instruments.

## Acknowledgements

 - [ETF Price & Volume Data - yfinance](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [ETF Fund Flows Data - etf.com](https://www.etf.com/etfanalytics/etf-fund-flows-tool)
 - [Sector Fundamental Data - Howard Silverblatt (S&P Global)](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwjbzq2FxN6BAxUHIsAKHWMgA4QQFnoECBkQAQ&url=https%3A%2F%2Fwww.spglobal.com%2Fspdji%2Fen%2Fdocuments%2Fadditional-material%2Fsp-500-eps-est.xlsx&usg=AOvVaw2GG1g3KSGmZwy7QiC8YI17&opi=89978449)
