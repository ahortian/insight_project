# insight_project
During the Insight Data Science Programe in Jun 2019, I bult "SafeGetaway" a web app that predicts crime occurrences during 
a visitor stay at an Airbnb in Boston. 
This repository contains jupyter notebooks which analyze data and build a model for the prediction.

## Get weather data
1. Scrape data from website using: `00_scraping_weather.ipynb`  
2. Aggregate the scraped data using: `01_weather_concat.ipynb`

## Create training dataset
1. Code: `03_data_prep_train_test_data.ipynb`  
   - Initial cleaning of data and 
   - Create training dataset
   - this script is also used for initial EDA & plotting  
2. Merge this data with weather data by: `04_data_prep_merge_with_weather.ipynb`

## EDA
1. Indepth EDA by : `05_EDA.ipynb`

## Baseline model : average over time
1. The calculation for the baseline model based on the average of crime occurrences over time is done by: `06_baseline_results.ipynb`
	
## Gradient Boosting model
1. This is done by: `07_model_performance.ipynb`
   - Also comparing the performance with logistic model
   
