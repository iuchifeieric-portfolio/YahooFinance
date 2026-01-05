# YahooFinance

![](images/InProgress.png)

## Library Used:
- yfinance
- pandas
- requests
- BeautifulSoup
- matplotlib

## Web Scraping Source:
- [Tesla Revenue 2010-2022](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/labs/project/revenue.htm)
- [GameStop (GME) Revenue 2006-2020](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/labs/project/stock.html)

## Stock Data Extraction
``` python
tsla = yf.Ticker('TSLA') # Ticker symbol
tesla_data = tsla.history(period='max') # Specify the period to be 'max'
```
![](images/StockData.png)

## Tesla Graph - Share Price & Revenue
![](images/tslaGraph.png)

## GME Graph - Share Price & Revenue
![](images/gmeGraph.png)
