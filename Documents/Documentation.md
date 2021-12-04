# TLC Trip Record Data Prediction Documentation

## Abstract

The pupouse of this project is to predict the fare amount of the trip using linear regression algoritm.
We worked with data provided by [TLC Trip Record Data](https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page).


## Design

This project originates from the Data Science Bootcamp (T5) to predict fare amount by using TLC trip record dataset through Linear Regression.

## Data

The dataset contains more than 141000 taxi rides with 20 features.
The dataset contains 2 csv files: 
* Green trip data for January 2021
* Green trip data for February 2021

|| Green trip data for January 2021 | Green trip data for February 2021 |
| --- | --- | --- |
| `Observations` | 76487 | 64541 |
| `Features` | 20 | 20 |
| `Data` | pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts. | pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts. |

You can see data description [HERE](https://www1.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_green.pdf).


## Algorithms

#### - ***Feature engineering:***
Converting dates to datetime type.
Extract months, week days, days,work days, hours and rush hours.
#### - ***Hot-one encoding:***
RatecodeID, Payment type and store and forward trip.
#### - ***Data Processing:***
Cleaning the data from duplicate, outliers and nulls.
#### - ***Linear regression model***

#### - ***Visualization***
  - Histograph plot
  - Pie chart
  - Scatter plot
  - Line plot

## Tools

- Python and Jupyter Notebook
- Numpy and Pandas for data manipulation
- Matplotlib and Seaborn for plotting visuialization
- Sklearn for LinearRegression


## Communication
Presentation.
