# Impact of COVID-19 on the Stock Market
## Team Members

Sayali Ambulkar

Meghana Palaparthi

Ishani Naik

Nivedita Chinnakannu
## Introduction
Sector-wise analysis of the impact of COVID-19 on one of the world’s biggest Stock Markets (S&P 500) and post-pandemic prediction of the same.

1. From https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset, the covid_19_data.csv file was downloaded.

2. From https://www.kaggle.com/paultimothymooney/stock-market-data, from sp500 --> csv, five datasets that were included in the S&P 500 Health Care Index (reference: https://www.barchart.com/stocks/indices/sp-sector/health-care) were downloaded.

3. Using DataRobot Paxata, the following steps were performed:

* Imported all the downloaded datasets.
* In covid_19_data.csv, removed unnecessary rows - the rows with any country other than the US were removed.
* Removed 4 unnecessary columns.
* Aggregated the values in the rows by merging rows with the same date.

4. This data was now ready to be merged with the Stock Market datasets.

5. This version of the covid_19_data dataset was merged with 5 of the Stock Market S&P 500 Health Care Index datasets (A.csv, ABBV.csv, ABC.csv, ABMD.csv, ABT.csv), merging on the date column.

6. The blank rows were removed.

7. The unnecessary columns were removed.

8. Now, we have a dataset containing the data for confirmed cases, deaths, recovered cases due to COVID-19, mapped with dates, for which we have the stock value information for the 5 companies from the S&P 500 Health Care Sector.

9. This dataset was exported from DataRobot and imported in the colaboratory notebook.

10. Exploratory data analysis was performed on this data.

11. In further analysis, graphs to show sector-wise comparison of the impact of COVID-19 will be added.

# Updated Notebook
## Group5_Project_intial_copy.ipynb
