## Hello!

UPDATED in July 2021, previous versions used Polygon.io as stock source.

Here is the link to the Tableau public dashboard of my data!
https://public.tableau.com/views/StockCorrelation/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link 
#### File Summary

stockdata.ipynb gathers stock data from the yfinance library and saves the historical prices to .csv files, found in the data file.
dataload.ipynb pushes the stock data collected in the previous file to a PostgreSQL Database.
portfolio.ipynb calculates the risk and return of binary stock portfolios and then writes data to .csv file for tableau. 

Thanks,

Jason Werenski
