# Rainfall in Singapore

## Project Introduction
The main goal of this project is to reinforce my understanding of an end-to-end machine learning project. The objectives of this project are as follows:
1. To practice fundamental data visualization and processing skills
2. To implement a variety of machine learning models, perform hyperparameter tuning and evaluate their performances
3. To build an ensemble regression model that predicts the total monthly rainfall in Singapore

### Methods Used
* Feature Selection
* Machine Learning
* Data Visualization
* Regression Analysis

### Technologies
* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn

## Project Description

### Data sources
The weather data used in this project are taken from [Data.gov.sg](https://data.gov.sg/).
The datasets are managed by Singapore's [National Environment Agency](https://www.nea.gov.sg/) (NEA), and they are recorded at the Changi Climate Station. 

### Data dictionary
|Variable  |  Description   | Type | Unit of measure|
|-------|-----------------|------|------|
|month| Months from Jan 1, 1982 to Jun 30, 2019| Datetime(Month) "YYYY-MM" | -
|monthly_total_rainfall | The total monthly rainfall| Numeric| Millimeter
|rh_extremes_minimum| The absolute extreme minimum relative humidity for the month| Numeric | Percentage
|no_of_rainy_days|The number of rain days (day with rainfall amount of 0.2mm or more)|Numeric| Days
|maximum_rainfall_in_a_day|The highest daily total rainfall| Numeric | Millimeter|
|mean_sunshine_hrs|The monthly mean sunshine hours in a day| Numeric| Hours|
|	temp_mean_daily_min|The monthly mean daily minimum temperature| Numeric | Celsius|
|temp_mean_daily_max|The monthly mean daily maximum temperature| Numeric | Celsius|
|temp_extremes_min|The absolute extreme minimum air temperature| Numeric| Celsius|
|max_temperature|The monthly extreme maximum air temperature recorded| Numeric| Celsius
|mean_temp|The monthly mean air temperature recorded| Numeric | Celsius|
|mean_rh| The monthly mean relative humidity recorded| Numeric |Percentage|

## License
The dataset used in this project is licensed under [Singapore Open Data License](https://data.gov.sg/open-data-licence).

## Acknowledgements
* Hands-On Machine Learning with Scikit-Learn and TensorFlow
* Python Machine Learning, Second Edition
* Yassine Ghouzam's [Titanic kernel](https://www.kaggle.com/yassineghouzam/titanic-top-4-with-ensemble-modeling) at Kaggle
* The kind-hearted and helpful Stack Overflow community

## Remarks
This is my first mini project as an aspiring self-taught machine learning engineer. Of course, I am always open to feedback and comments! If you wish to have a personal chat with me, you can find me on [LinkedIn](https://www.linkedin.com/in/jonathanseow5177/). 
