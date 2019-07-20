# price_analysis_with_airbnb

### Motivation
This project aims to understand the price behaviour in Seattle and Boston using Airbnb Data. The project is required for completing the Udacity's Data Scientist Nanodegree course.

The main motivation of this project is how to use real world data to answer business questions following a CRISP-DM approach.

### Files in this Repository
This repository contains the following files:

README.MD: the present file

project_jupyter.ipynb: all the analysis made in the project

boston/calendar.csv: contains booking data (such as date and availability) for Boston (July 2019).

boston/listings.csv: contains detailed listings data for Boston (July 2019).

seattle/calendar.csv: contains booking data (such as date and availability) for Seattle (July 2019).

seattle/listings.csv: contains detailed listings data for Seattle (July 2019).

Notice: all the files belongs to Airbnb an can be obtained here: http://insideairbnb.com/get-the-data.html

### Business Questions
This project was motivated by the following main questions:

- How do the prices varies over time? Is it possible to identify seasonal behaviours?
- Do the prices vary considerably from one city to another?
- Is it possible to predict the listing price for in a certain city?
- What characteristics are most related to prices changes?

### Results
- It was possible to model the listing price using a Random Forest Regressor, with mean r2 test score of 0.438 in a 5-fold cross validation.
- The data suggests that prices are higher between July and September and lower between November and March for both cities.
- Both cities present a left skewed price distribution, suggesting that prices are more concentrated at lower values.
- Some of the features that are most related with the listing price in Seattle are the Host Response Rate, the number of Bedrooms and the presence of a Pike Place Market. Moreover, those featuers are positively correlated with the price.

### Used Libraries
The python libraries used in this project were the following:
- pandas
- numpy
- sklearn.linear_model
- sklearn.ensemble
- sklearn.preprocessing
- sklearn.feature_selection
- sklearn.model_selection 
- sklearn.pipeline
- sklearn.metrics
- matplotlib
- seaborn

### Acknowledgements
I would like to ackonwledge Udacity and Airbnb

### License
The data used in this project belongs to Airbnb under the Creative Commons CC0 1.0 Universal (CC0 1.0) "Public Domain Dedication" license.
