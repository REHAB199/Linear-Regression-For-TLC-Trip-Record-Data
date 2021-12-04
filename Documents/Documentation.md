# TLC Trip Record Data Prediction

## Abstract

The pupouse of this project is to predict the fare amount of the trip using linear regression algoritm.
We worked with data provided by [TLC Trip Record Data](https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page).


## Design

This project originates from the Data Science Bootcamp (T5) to predict fare amount by using TLC trip record dataset through Linear Regression.

## Data

The dataset contains more than 141000 taxi rides with 20 features.
- VendorID - A code indicating the LPEP provider that provided the record.
- lpep_pickup_datetime - The date and time when the meter was engaged.
- lpep_dropoff_datetime - The date and time when the meter was disengaged.
- Passenger_count - the number of passengers in the vehicle driver entered value.
- Trip_distance - The elapsed trip distance in miles reported by the taximeter.
- PULocationID - TLC Taxi Zone in which the taximeter was engaged.
- DOLocationID - TLC Taxi Zone in which the taximeter was disengaged.
- Payment_type - A numeric code signifying how the passenger paid for the trip.
  * 1 = Credit card
  * 2 = Cash
  * 3 = No charge
  * 4 = Dispute
  * 5 = Unknown
  * 6 = Voided trip

You can see more of the data description [HERE](https://www1.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_green.pdf).


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
