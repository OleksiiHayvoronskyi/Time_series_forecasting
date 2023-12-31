			
# <center>Time Series Analysis – USA Real Estate Dataset</center>
			
## Overview

This repository contains code and documentation for performing time series analysis 
on the USA Real Estate Dataset.
<br>You can download the dataset to the next link:
<br>*https://www.kaggle.com/datasets/ahmedshahriarsakib/usa-real-estate-dataset/data*

In this project, I focused on time series analysis, exploring trends, 
<br>studying past patterns, and making meaningful future predictions
<br>related to real estate prices over time.
<br>For this purpose, I employed the Holt-Winters, SARIMAX, and ARIMA algorithms.
<br>At the end of the analysis, I compared all these models to determine
<br>which one performed better.


## Dataset

**The USA Real Estate Dataset** is used for this analysis.
<br>This dataset contains Real Estate listings in the US broken by State and zip code.

**Content**

The dataset has 1 CSV file with 10 columns:

1. status (Housing status - a. ready for sale or b. ready to build)
2. bed (# of beds)
3. bath (# of bathrooms)
4. acre_lot (Property / Land size in acres)
5. city (city name)
6. state (state name)
7. zip_code (postal code of the area)
8. house_size (house area/size/living space in square feet)
9. prev_sold_date (Previously sold date)
10. price (Housing price, it is either the current listing price 
           or recently sold price if the house is sold recently)


## Project Structure

1. Required libraries.
2. Data analysis and preprocessing.
<br>2.1. Removing columns and missing values.
<br>2.2. Converting the 'Date' column into a datetime format.
<br>2.3. Splitting the 'Date' column into a year, a month and a day.
<br>2.4. Index definition.
3. Data visualisation.
<br>3.1. Resampling and interpolating data.
<br>3.2. Statistics, characteristics, and evaluation of the distribution of current data.
<br>3.3. Time-Series data visualization.
4. The Dickey-Fuller Test.
5. Making non-stationary time series to stationary.
<br>5.1. First-Order Differenced Time Series.
<br>5.2. The Dickey Fuller test after First-Order Differenced Time Series.
<br>5.3. Comparison the original and stationary series.
6. Splitting into trend, seasonality and residuals (noise component), and analyze.
7. ACF and PACF analysis.
8. Splitting into Train and Test data.
9. Holt Winters Algorithm.
<br>9.1. Metrics of Holt-Winters Algorithm.
10. SARIMAX Algorithm.
<br>10.1. Finding the optimum parameters with Auto-arima.
<br>10.2. Training SARIMAX model.
<br>10.3. Metrics of SARIMAX model.
11. ARIMA Algorithm.
<br>11.1. Finding the optimum parameters with Auto-arima.
<br>11.2. Training ARIMA model.
<br>11.3. Metrics of ARIMA model.
12. Comparison: ARIMA vs SARIMAX vs Holt-Winters.
13. Saving ARIMA model.


## Prerequisites

Ensure you have the following installed:
- Python 3.x
- Jupyter Notebook (optional)
- IDE: PyCharm or Visual Studio
- Required Python libraries (pandas, numpy, matplotlib, statsmodels, scikit-learn, etc.)


## Install dependencies
- pip install -r requirements.txt

## Usage

Clone this repository:
*git clone https://github.com/OleksiiHayvoronskyi/Time_series_forecasting/blob/master/USA_Real_Estate_time_series_forecasting.ipynb*


## Contributors
***Oleksii Haivoronskyi***





			