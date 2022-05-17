# Investment Portfolio based on Piotroski Score

## Objective

The objective of this project is to calculate the Piotroski score for all the stocks in the SP500, create a portfolio based on these scores, and analyze how this portfolio would perform against the SP500.<br>
Piotroski F-Score is calculated based on 9 criteria divided into 3 groups: Profitability, Leverage and Operating Efficiency.<br><br>
We will analyze the annual return of these stocks, grouped by Piotroski Score, to see if the top stocks perform significantly better than the SP500 index.<br>
And to conclude, we will create an investment portfolio with the stocks with the highest score to compare returns and analyze volatility of our new portfolio.<br>

## Datasets

### yahoo_fin library <br>
Link: http://theautomatic.net/yahoo_fin-documentation/<br><br>
To download the Financial Statements (Income Statement, Balance Sheet and Cash Flow) for each company in the SP500 to calculate the 9 Piotroski scores.<br><br><br>
### SP500 info and share prices (daily updated) from Kaggle (in the folder Datasets)<br>
Link: https://www.kaggle.com/datasets/andrewmvd/sp-500-stocks?datasetId=1807380&sortBy=voteCount<br><br>
This contains 3 csv files:
-	sp500_companies.csv: Company metadata for S&P500 companies
-	sp500_index.csv: S&P500 share prices
-	sp500_stocks.csv: Share prices for each stock included in the S&P500
To have the historical share prices of the SP500 index and all the stocks included in this index, to be able to compare the performance of the index and the newly created portfolio.<br><br><br>
### The csv extracted, from a previous run of this project, from the datasets summary and log_file (in the folder Dataframes_Extract)<br>
-	20220507_fy2020_Log: Log for all the tickers downloaded form yahoo_fin<br>
-	20220507_fy2020_Summary: Data for all the tickers downloaded from yahoo_fin, including the calculated Piotroski Scores<br>
After the download, from the Notebook, these files have been renamed adding date and fiscal year.<br>
