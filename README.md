# UDACITY - Data Science Nanodegree - Project 1

## CRISP-DM process

### Business Understanding

Seattle AirBnB data that will be explored in notebook attached to this repository should provide us with information about how is pricing shapping across the Seattle locations listed on AirBnB. We will dig into few questions that and try to provide answers to them in order to have better understaning on what influences the prices.

Question that I would like to answer:
How prices are shaped based on the neighborhood in which property is located?
Is there a significant difference between the types of properties in terms of price?
Based on the location can we determine that some parts of Seattle tend to have higher prices than others?
Are any months in which prices are higher or more rental properties are rented?
Do properties that require a deposit have better reviews than the ones without a deposit required?

### Data Understaning

Provided data for the course consists of 3 files:
- calendar.csv - contains when listing was rented and for what price
- listings.csv - contains all the information about listings including neighborhoods, prices, deposits, additional costs, reviews score, etc.
- reviews.csv - contains reviews from the user - in this analysis we will not be using this one most likely

Given correct tools and data manipulation we can prepare our data and shape them to provide good answer to our questions

### Data Exploration

Please refer to jupyter notebook attached to this repository for the data exploration

### Modeling

This data analysis is purely exploratory. At this point I will not be using any machine learning techniques.

### Evaluate and results

I believe that all the questions has been answer and delivered better understanding on how market is shaped in Seattle for listings on AirBnB.
The results of the analysis can be found in Medium.com article:
https://medium.com/@m.dyngosz/breaking-into-data-science-world-airbnb-seattle-data-f554ec879e37

## Tools used for analysis

* *pandas* - data analitics library for computing and data manipulation
* *NumPy* - data processing library
* *matplotlib* - data visualization library
* *seaborn* - data visualization library build on top of matplotlib

## Files description

- Seattle_Airbnb.ipynb - notebook containing all the data exploration
- /article_data/ - this folder contains all the graphics used for medium.com article
- /seattle/ - this folder contains all the files with data used for the exploration - details are described above
