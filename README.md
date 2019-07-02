# insight_project

## Get Weather Data
(1) scrape data from website using: scraping_weather_v4.ipynb  
(2) aggregate the scraped data using: weather_concat.ipynb

## Create training dataset
(1) create training dataset by: segment_map_time_reduce_police_random.ipynb  
	(1.1) this script is also used for EDA & plotting  
(2) merge this data with weather data by: train_data_merge_weather_hourgroup_police_rand.ipynb

## Basedline model : Mean
(1) the calculation for the baseline model based on the average of crime over time is done by: performance_with_police_rand.ipynb
>> original name: 2019_06_28_test_performance_with_police_rand_nocyclic.ipynb
	

## BDT model
(1) this is done by: performance_with_police_rand_downsampling.ipynb
>> original name: 2019_06_28_test_performance_with_police_rand_nocyclic_downsampling.ipynb

