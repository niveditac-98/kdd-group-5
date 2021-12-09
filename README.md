# Analysis of the impact of COVID-19 on the Stock Market across different sectors and post-pandemic prediction of the same.
## Team Members

Sayali Ambulkar

Meghana Palaparthi

Ishani Naik

Nivedita Chinnakannu

## Introduction
Sector-wise analysis of the impact of COVID-19 on one of the world’s biggest Stock Markets (S&P 500) and post-pandemic prediction of the same.
Sectors considered: Healthcare, IT, Industrials.

## Data Sources
We used the data available at the following links:

https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset
https://www.kaggle.com/paultimothymooney/stock-market-data
https://www.kaggle.com/gpreda/covid-19-vaccination-progress/data

# Domain understanding
We deemed it would be of great use to individuals and businesses to know how variations in confirmed cases and deaths due to COVID-19 affected stock prices in different business sectors. In our project, we are trying to predict the stock prices of companies in three different sectors namely health care, IT and industrials based on COVID-19 cases.

# EDA
Our main purpose is to highlight the impact of rising COVID-19 cases and the introduction and progress of vaccinations on the stock prices of the companies within these sectors. One example (healthcare sector) is shown below.

# Data Preparation
We performed data cleaning by dropping duplicate values, dropping rows with null values, dropping unnecessary/irrelevant columns, changing the column datatypes, changing date formats. This was done using a combination of DataRobot Paxata and Python. We then merged the covid dataset with the 5 companies of the sector under consideration, on the date column. This step was repeated for all three sectors.

# Data Modeling
We have used Multiple Linear Regression to perform prediction of Stock prices based on COVID-19. Multiple Linear Regression is a statistical technique that uses several explanatory variables to predict the outcome of a response variable. Here, we estimate the relationship between COVID-19 confirmed cases, deaths, recovered cases and the closing stock price of companies in each sector.

# Evaluation
Our model generates a **MSE of 0.01 and Prediction Score of 0.99**

# Conclusion
Using DataRobot Paxata and Python we have merged the S&P 500 health care sector datasets, IT sector datasets, and industrials sector dataset along with the covid_19 dataset, joining on date.
We have used linear regression as our prediction model and mean square error as our evaluation model. The basic idea of our evaluation model is to measure how bad/erroneous the model's predictions are when compared to actual observed values.
Our prediction model has an accuracy of 0.99 and the mean square error is 0.01.

We had faced a problem with finding a model suitable to our prediction requirements. As per our understanding, algorithms like ARIMA, Facebook Prophet accepted only one attribute/feature, whereas we had five different features in our cleaned data.
We then found and implemented the Multiple Linear Regression model.

# Future Scope
With further calculations, we may also be able to predict the values of **sector indices** in the S&P 500 market. With a similar approach, we can predict the impact of COVID-19 on different sectors (other than healthcare, IT, and industries).

Note: This project includes the prediction of stock values based on certain data. The model has to be trained on labeled data in order to make a labeled prediction.
For analysis in this project, labeled data is necessary in order to understand and interpret the results of the analysis. For example, in the year 2021, an increase in the number of vaccinations per day resulted in an increase in the day’s high for the stock value of Agilent Technologies. This analysis would have been difficult if the data was unlabeled.
