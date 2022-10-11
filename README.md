# Bike Sharing Assignment


## Table of Contents
* [Problem Statement](#problem-statement)
* [Business Objective](#Business-objectives)
* [Approach Used](#Approach-used)
* [Observations & Results](#observations-&-results)



## Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

## Business Objectives
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 


## Approach Used
- Understanding the data.
- Perform the Data Cleaning.
- Perform Label Encoding & Visualization
- Visualize the Relationship Among the Variables (Categorical & Numerical)
- Created the Dummy Variables for Categorical Variables.
- Split the Data into Training and Testing Dataset.
- Perform Scaling of Features.
- Perfomm Recursive Feature Elimination Technique and later use statsmodel for detailed statistics.
- Perform Residual Analysis of train data.
- Make the Prediction: Aplly the scaling on test sets, dividing X_test and Y_test.
- Perform Model Evaluation : PLot graph between y_test & y_pred, Calculating R^2, Calculating Mean Squared Error.
- Observed the driving factors behind demand of shared bikes.   


## Observations & Results
From the above Analysis, We conclude that: 
Observations:

- The Variables temp, yr, weather(cloudy), season(winter, spring), month(september, may, july), day(Saturday), workingday, windspeed, hum will be significant to have an impact on demand for shared bikes.

- Temperature will play a significant role in demand of shared bike.

- There are some features having negative coefficient, those features will decrease the demand for shared bike.

- Year 2019 shows great demand than 2018, so we can say that upcoming year will have increase in demand. So they should follow the same patterns followed in 2019.

- Cloudy weather shows an decrease in demand of bike.

- September has an increase in demand followed by may. While, July shows decreasee in demand.

- Winter will have an increase in demand. while, Spring will show decrease in demand.

- Working days will be having increase in demand.

- windspeed & humidity shows an negative effect on demand of shared bikes


## Contact
Created by [@SajagChauhan] - feel free to contact me!
