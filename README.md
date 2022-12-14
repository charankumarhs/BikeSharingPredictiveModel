# Shared Bikes Multiple Linear Regression Machine Learning Model
This is part of Linear Regression Model demonstartion on a shared-bikes data, from the skilles gained during the course study

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

#### Essentially, the company wants to know - 
* The factors/features affecting the demand
* Which variables are significant in predicting the demand for shared bikes.
* How well those variables describe the bike demands

### Business Goal:
Build a linear regression machine learning model to predict the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.


## Conclusions

Equation of the best fitted linear regression predidictive model to predict the shared bikes demand with 12 feature selected from the data set given is,

### $ SharedBikeCount \, = \, 0.5348 + \,0.2461 * yr\, + \,0.0571 * workingday\, - \,0.1926 *  windspeed\, - \, 0.2376 * spring\, - \,0.0385 * summer\,  -  \,0.1232 * january\, +\,0.0563 * september\, - \,0.1122 * november\, - \,0.1183 * december\, + \,0.0664 * monday\, -\,0.0890 * weathersit_2\, - \, 0.3202 * weathersit_3$ 

NOTE: 
* weathersit_2 : Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist<br>
* weathersit_3 : Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
* january, september, november, december are the categories of the feature mnth with values 1, 9, 11, 12 respectively.
* summer and spring are categories of season with category value 1 and 2 in the data set
* monday refers to value 6 in the weekday feature in the data set

The linear regression model is 78.52% accurate with 70% training and 30% test data set.


## Technologies Used
- library -  pandas  version  1.4.3
- library -  numpy  version  1.21.5
- library -  seaborn  version  0.11.2
- library -  matplotlib  version  3.5.2
- library -  sklearn  version  1.1.1
- library -  statsmodels  version  0.13.2
- library -  sweetviz  version  2.1.4
- library -  scipy  version  1.7.3
- library -  warnings

## Acknowledgements

- This project was done as part of the Machine Learning and Artificial Intelligence Master Degree program by upGrad in asssociation with IIIT-B and LJMU.


## Contact
Created by [@charankumarhs] - feel free to contact me!
