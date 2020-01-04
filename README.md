# insight_project
At Insight, I bult "SafeGetaway" a web app that predicts crime incidents during 
a visitor stay at an Airbnb in Boston. 
This repository contains jupyter notebooks which analyze data and build a model for the prediction.

## Get Weather Data
1. scrape data from website using: `scraping_weather_v4.ipynb`  
2. aggregate the scraped data using: `weather_concat.ipynb`

## Create training dataset
1. create training dataset by: `segment_map_time_reduce_police_random.ipynb`  
   - this script is also used for EDA & plotting  
2. merge this data with weather data by: `train_data_merge_weather_hourgroup_police_rand.ipynb`

## Baseline model : Average over time
1. the calculation for the baseline model based on the average of crime over time is done by: `performance_with_police_rand.ipynb`
	
## BDT model
1. this is done by: `performance_with_police_rand_downsampling.ipynb`


