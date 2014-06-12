---
title       : Permanent Portfolio Analyzer Web App
subtitle    : Allows users to simulate a portfolio equities, bonds and commodities.
author      : Ng Wai Chung
job         : Pre-matriculant with the SMU JD program.
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}

---

## Motivation

1. Investors would like to maximise returns but minimize their risks.
2. Equities or stock have large returns but comes with larger risks.
3. Bonds have lower returns but it comes with a much lower risk
4. Commodities provide diversification from equities and bonds.
5. There is a motivation to creare a tool which allows investor to determine an asset which suits his risk appetite.

---

## Permanent Portfolio Web Application

1. Decomposes a stock time series into trend, seasonal and random components.
2. Selects from 3 popular Exchange Traded Funds available in the Singapore Stock Market.
3. Covers the main stock, bonds and commodities asset classes.
4. The user can blended these ETFs to create an asset mix.
5. The user will be able to observe the changes in portfolio returns and standard deviations on this page.

--- .class #id 

## Decomposition of the Singapore Stock Market Equity Index


```
## Error: could not find function "decompose_stock"
```



```
## Error: object 'final_plot' not found
```


--- .class #id 

## Decomposition of balanced portfolio
### ( 34%/33%/33% mix of Equity/Bond/Commodities )


```
## Error: could not find function "perm_portfolio"
```


--- .class #id 

## Some points on how this app works

1. Decomposes a stock time series into trend, seasonal and random components.
2. Selects from 3 popular Exchange Traded Funds available in the Singapore Stock Market.
3. Covers the main stock, bonds and commodities asset classes.
4. The user can blend these ETFs to create an asset mix.
5. The user will be able to observe the changes in portfolio returns and standard deviations on this page.
6. This program takes into account broker cost when the portfolio is rebalanced on an annual basis. 
