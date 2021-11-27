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

<img width="394" alt="abbvie inc" src="https://user-images.githubusercontent.com/91848959/143666994-9fdd5b03-b3a5-472c-854b-f0b3b6a49b16.PNG">
<img width="415" alt="abiomed" src="https://user-images.githubusercontent.com/91848959/143666995-0df96533-d17c-4562-a6af-261e58371216.PNG">
<img width="334" alt="Abott labs" src="https://user-images.githubusercontent.com/91848959/143666996-fe151a85-7ac4-42bd-9f6e-3787544e30b3.PNG">
<img width="400" alt="Agilent tech" src="https://user-images.githubusercontent.com/91848959/143666997-bc0d72d9-d981-4238-b2e3-b440f2165092.PNG">
<img width="413" alt="amisourcebergen corp" src="https://user-images.githubusercontent.com/91848959/143666998-3911e726-66c0-445a-a272-db099afa9972.PNG">
<img width="813" alt="Covid" src="https://user-images.githubusercontent.com/91848959/143667000-d3aed740-5f31-4f1c-bff9-6a08a0452ae3.PNG">


11. In further analysis, graphs to show sector-wise comparison of the impact of COVID-19 will be added.

This project includes the prediction of stock values based on certain data. The model has to be trained on labeled data in order to make a labeled prediction.
For analysis in this project, labeled data is necessary in order to understand and interpret the results of the analysis. For example, in the year 2021, an increase in the number of vaccinations per day resulted in an increase in the day’s high for the stock value of Agilent Technologies. This analysis would have been difficult if the data was unlabeled.

# Updated Notebook
## Group5_Project_Initial_Copy.ipynb
## updated dataset : https://drive.google.com/file/d/1-TtN2fRqFhXLtuS_gCFe7rqkl5jgMFF-/view?usp=sharing
