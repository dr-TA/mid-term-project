# mid-term-project
The goal of this project is to predict arrival delays of commercial flights. 

Files

cleaning.ipynb: this file contains steps taken to clean the data

XGBoost.model.ipynb: this file contains the XGBoost model training and feature selection.

Preds.xgb.ipynb: this file is used to make predictions based on the saved XGBoost model and df_flights_test.csv.

Data
I worked with data from air travel industry (four separate tables)

flights: The departure and arrival information about flights in US in years 2018 and 2019.
fuel_comsumption: The fuel comsumption of different airlines from years 2015-2019 aggregated per month.
passengers: The passenger totals on different routes from years 2015-2019 aggregated per month.
flights_test: The departure and arrival information about flights in US in January 2020. This table will be used for evaluation. For submission, we are required to predict delays on flights from first 7 days of 2020 (1st of January - 7th of January). We can find sample submission in file sample_submission.csv
The data are stored in the Postgres database. You can see the information about the hostname and credentials in Compass.
