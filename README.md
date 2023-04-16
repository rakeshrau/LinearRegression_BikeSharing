# Bike Sharing-Linear Regression

## Business Objective:
A US bike-sharing provider BoomBikes have contracted a consulting company to understand the factors on which the demand for the shared bikes depends. Specifically, they want to understand the factors affecting the demand for the shared bikes. The company wants to know:

1.Which variables are significant in predicting the demand for shared bikes.

2.How well those variables describe the bike demands.

We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 


## Table of Contents
* [Dataset](#Dataset)
* [Technologies](#Technologies)
* [Conclusions](#Conclusions)
* [Contributors](#Contributors)


## Dataset
- 'day.csv' dataset is used,which is dataset on daily bike demands across the American market based on some factors. 

## Technologies
- Python-3.7.3
- Pandas-0.24.2
- Numpy-1.16.4
- Matplotlib-3.1.0
- Seaborn-0.9.0
- Statsmodels-0.10.0
- Scikit-learn-0.21.2

## Conclusions
- Temperature(temp) has largest positive co-efficient so an increase in temperature has maximum impact on the number of rides.
- Year, Seasons(Summer,Winter) and month(September) also have positive impact on increase in number of rides.
- Windspeed,Sunday and Weather(Misty,Light_SnowRainThunder) factors cause a decrease in number of rides.
- Months(January,February,July,November,December) causes a decrease in number of rides.

## Contributors
Created by [@rakeshrau] - Rakesh Raushan
