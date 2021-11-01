# Impact of Covid-19 on stock market
## Team Members

Sayali Ambulkar

Meghana Palaparthi

Ishaani Naik

Niveidta Chinnakannu
## Introduction
Analysis of the impact of COVID-19 on two of the world’s biggest Stock Markets (NYSE and NASDAQ) and post-pandemic prediction of the same.
From https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset, we downloaded the covid_19_data.csv file.
From https://www.kaggle.com/paultimothymooney/stock-market-data, from sp500 --> csv, we downloaded five datasets that were included in the S&P 500 Health Care Index (reference: https://www.barchart.com/stocks/indices/sp-sector/health-care)
Using DataRobot Paxata, we performed the following steps:
Imported all the downloaded datasets.
In covid_19_data.csv, we removed unnecessary rows - the rows with any country other than the US was removed.
Removed 4 unnecessary columns.
Aggregated the values in the rows by merging rows with the same date.
This data is now ready to be merged with the Stock Market datasets.
We join this version of the covid_19_data dataset with one of the Stock Market datasets (A.csv, which is the data for Agilent Technologies).
We remove the blank rows post-joining.
We remove the unnecessary columns.
Now, we have a dataset containing the data for confirmed cases, deaths, recovered cases due to COVID-19, mapped with dates, for which we have the stock value information for Agilent Technologies, which is one of the companies from the S&P 500 Health Care Sector.
We have exported this dataset from DataRobot and imported it below.
