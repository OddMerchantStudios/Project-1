# Historical Index, Sector and Stock Market Analysis

## Questions:
 
### Analysis Framework:

#### **Market Statistics Report:**
1. Review stock, index and stock performance over 1, 5 and 10 year windows.
2. Show relationships between indexes, sectors and stocks.
3. Rank order and identify top performing indexes, sectors and stocks within the time periods selected.
4. Identify relationships between the time periods - which indexes and stocks perform consistently?
5. Identify top 10 most efficient stocks per the sharpe ratio for further portfolio development and analysis.

#### **Fundamental Report:**
6. Identify best value and growth portfolio stocks for further portfolio development and analysis.

#### **Optimal Portfolio Simulated Returns and Analysis:**
7. Run MC simulations on best set of value, growth and sharpe ratio portfolios across 1,5 and 10 year time periods.
8. Identify which equal weighted portfolio performs best in a scenario analysis.
9. Summarize optimal portfolio findings.



# Report 1 : **Market Statistics Report**

## ***Overview of Indexes, Sectors and Stocks used in analysis:***

### **Indexes**:

- **DIA** - Dow Jones Industrial Average
- **SPY** - S&P 500
- **QQQ** - Nasdaq 100
- **IWM** - Russell 2000

### **Sectors**:

- **IYC** - Consumer Discretionary
- **IYH** - Healthcare
- **IYK** - Consumer Staples
- **IYR** - Real Estate
- **IYZ** - Communication Services
- **XLB** - Materials
- **XLE** - Energy
- **XLF** - Financials
- **XLI** - Industrials
- **XLK** - Technology

-------------------
## ***Optionable Stock Universe:***
#### We did not use all 5,000+ stock tickers for this analysis but limited our analysis to what we called the “Optionable Stock Universe”, this universe is defined by stocks that have the following characteristics:
- Options securities available to trade
- Weekly expiration dates on options available to trade
- Tight bid-ask spreads = liquidity on weekly options expirations
-  \> 1 MM in average daily stock trading volume 
-----------------
## ***Performance Analysis Framework:***
### Our analysis methodology focused on 3 key metrics:  
- Mean Returns (annualized)
- Standard deviation of Returns
- Sharpe Ratios of Index, Sector or Stock (assumes 1 index, sector or stock portfolio)
-----------------------
## **We utilized 3 different time periods for analysis:**
- 1 year
- 5 years
- 10 years

------------------------------
### - The objective was to identify which index, sectors and stocks were more or less correlated; and which indexes, sectors and stocks produced the best sharpe ratios as a proxy for most efficient returns per unit of risk.  The top performing sharpe ratio stocks would then be utilized in creating optimal portfolios for future returns and risk forecasting. 

### - Initial performance analysis for index and sectors show us a couple of key trends and insights:

### - Ranking performance by indexes:



# Report 2

## STOCK EARNINGS AND FUNDAMENTALS REPORT


ARNINGS TRADE ANALYSIS
* Company/Sector Fundamental Analysis:
### Value Metrics
* P/E 
* P/S
* P/B
### Growth Metrics
* EPS Growth Rates - 1 year
* EPS Growth Rates - 5 year
* PEG Ratio
### Accounting Returns and Margins
* ROA
* ROE
* ROI
* Gross/Net Margins
### Earnings**
* Revenue surprise - Y/N
* Revenue surprise % +/-
* Earnings surprise - Y/N
* Earnings surprise % +/-
----------------------------------------
### Earnings returns Hypothesis Analysis
- Null Hypothesis:  There is no difference in Risk/Returns/Sharpe Ratio within the quarterly earnings window (+/- 10 trading days) vs outside the earnings window (172 days)
- Alternative Hypothesis:  There is a difference between key statistical metrics within the +/- 10-day quarterly window vs. outside the earnings window
----------------------------------------
### Analyze:
* Returns
* Standard deviation
* Sharpe Ratio
* Earnings Report Surprises:
* Revenue
* EPS
## Forward Guidance
- Within 80 earnings period trading days vs. 172 outside earnings trading days


# Report 3

## PORTFOLIO ANALYSIS

### Based on the analysis above, given stock returns and risks, what is the optimal investment portfolio to maximize returns and minimize risk for a given return timeframe:
- 6 months
- YTD
- 1 year
- 3 year
- 5 year
- 10 year 

#### Looking to maximize Sharpe ratio, maximize returns and minimize risk


# Report 4 (Optional)

## MARKET TREND REPORT**

- Weekly reports around bullish, bearish and neutral trending sectors and stocks
- Apply basic trend rule logic to charts to isolate best potential trading opportunities.
- Looking at daily, 6 month charts only
- Utilize three basic indicators: EMA's, squeeze, Bollinger bands
- SMA's aligned?  
    - 8 above 21, 21 above 50, 50 above 200?
- Any Squeeze indicator opportunities?
- SMA/s trending up for bulls, down for bears, flat for neutral
- Instead of eyeballing, use rules-based criteria to define trends and codify reports



## Notebooks
- [JUPYTER LAB NOTEBOOK LINK](./main.ipynb)
- [Final Analysis](./file.ipynb)

## Plots
- PLOTS WILL GO HERE 

---
​
![Plot1](./assets/images/plot_image.png)
​
​
## Explanation

### Analysis Conclusion:
- 
​

## Additional Research Topics
- 


## Getting Started

### Prerequisites
​
​You must have Python 3 installed

```
python3 --version
```

You must have Anaconda installed
```
$ anaconda --version
```


### Install Environmnet
```
conda create -n <env_name> python=3.7 anaconda
```

### Clone/Run Repository 
```
git clone git@github.com:vkhorozian/Project-1.git
```

### Activate Environment
```
conda activate <env_name>
```

### Install Dependencies
- Please make sure you are in your intended activate environment before running this command
```
pip install -r requirements.txt
```


## Built With

- [![Python 3.7.13](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)]([https://www.python.org/downloads/release/python-3713/)
[![Python](https://img.shields.io/badge/Python-3.7.13-blue)](https://www.python.org/downloads/release/python-3713/) - Programming Language
- [![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/docs/#) - Data maniupulation library
- [![Numpy](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/) - Multi-dimensional array library
- [![Plotly](https://img.shields.io/badge/Plotly-239120?style=for-the-badge&logo=plotly&logoColor=white)](https://plotly.com/python/) - Visualization library for plots
- [![Matplotlib](https://img.shields.io/badge/Matplotlib-3776AB?style=for-the-badge&logo=plotly&logoColor=white)](https://matplotlib.org/) - Visualization library for plots
- [![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=plotly&logoColor=white)](https://seaborn.pydata.org/) - Visualization library for plots
- [![Alpaca](https://img.shields.io/badge/Alpaca-3776AB?style=for-the-badge&logo=plotly&logoColor=white)](https://alpaca.markets/) - Trading API
- [![HVPlot](https://img.shields.io/badge/HVPlot-3776AB?style=for-the-badge&logo=plotly&logoColor=white)](https://hvplot.holoviz.org/) - Visualization library for plots
- [![PyViz](https://img.shields.io/badge/PyViz-3776AB?style=for-the-badge&logo=plotly&logoColor=white)](https://pyviz.org/) - Visualization library for plots
- [![GeoViews](https://img.shields.io/badge/GeoViews-3776AB?style=for-the-badge&logo=plotly&logoColor=white)](https://geoviews.org/) - Visualization library for plots
- [![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white)](https://jupyter.org/) - Notebook IDE
- [![JupyterLab](https://img.shields.io/badge/JupyterLab-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white)](https://jupyter.org/) - Notebook IDE
- [![Anaconda](https://img.shields.io/badge/Anaconda-44A833?style=for-the-badge&logo=anaconda&logoColor=white)](https://www.anaconda.com/) - Data science platform
- [![Yahoo Finance API](https://img.shields.io/badge/Yahoo%20Finance%20API-800080?style=for-the-badge&logo=yahoo&logoColor=white)](https://pypi.org/project/yfinance/) - Yahoo Finance API

## Authors
- **Varoujan John Khorozian** - [LinkedIn](https://www.linkedin.com/in/varoujan-khorozian/) | [Github](https://github.com/vkhorozian)
- **Kirill Chugunov** - [LinkedIn](https://www.linkedin.com/in/kirill-chugunov-b680811a4/) | [Github](https://github.com/OddMerchantStudios)
- **Hiren Patel** - [LinkedIn](https://www.linkedin.com/in/hdpatel/) | [Github](https://github.com/hpnhs25)
