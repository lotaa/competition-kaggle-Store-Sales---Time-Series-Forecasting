# competition kaggle Store Sales Time Series Forecasting

# Goal of the Competition
In this “getting started” competition, you’ll use time-series forecasting to forecast store sales on data from Corporación Favorita, a large Ecuadorian-based grocery retailer.

Specifically, you'll build a model that more accurately predicts the unit sales for thousands of items sold at different Favorita stores. You'll practice your machine learning skills with an approachable training dataset of dates, store, and item information, promotions, and unit sales.

# DATASET
 - I Get dataset From kaggle API
 - 1 -train.csv
 - 2 -test.csv
 - 3 -stores.csv
 - 4 -oil.csv
 - 5- holidays_events.csv

# Code and Resources Used

- Python Version: 3.7 Packages: pandas, numpy, sklearn, matplotlib, seaborn, pickle

# EDA
![relation_city_sales](https://user-images.githubusercontent.com/49419507/146873254-6873d94d-74a5-4a7f-8f13-4a10062f1c72.png)
![trans](https://user-images.githubusercontent.com/49419507/146873270-d0c4ffef-9ffb-469a-a981-fe3642970650.png)
![locale_sales](https://user-images.githubusercontent.com/49419507/146873379-e46b550f-00d4-4b06-abe5-0d167084b010.png)


# Model Building
First, I transformed the categorical variables into dummy variables. I also split the data into train and tests sets. I tried 
xgboost as baseline
![accuracy](https://user-images.githubusercontent.com/49419507/146873763-5e0fbc7d-242a-43c0-bff1-61a07e800e4e.png)

# Preduction:
![pred](https://user-images.githubusercontent.com/49419507/146873904-e0eb1094-8ecd-4794-b6e6-e1c843d44515.png)
