# Bike Sharing Assignment
> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Libraries Used](#technologies-used)




## General Information
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario.
- BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19.
- The company wants to know Which variables are significant in predicting the demand for shared bikes and how well those variables describe the bike demands.They want a model that will be used by the management to understand how exactly the demands vary with different features.
- The dataset has 16 distinct columns and 730 rows.


## Conclusions
- Based on the heatmap and scatter plot, temp and atemp are highly correlated.
- cnt is correlated with yr,temp and atemp.
- Significant variables as per the final model are yr,atemp,windspeed,spring,winter,Jul,Sept and Light Snow.
- R2 score of the final model is 0.789 which means 78.9 % of variance in the data is explained by the model and Adj. R-squared of the model is 0.785 or 78.5% which is very close to our R2 score.
- F-statistics of the final model is 233.9 which means model fits very well overall
- Test R2 - 0.806 and  Test Adjusted R2 - 0.776



## Libraries Used
- python 3.10.9
- numpy 1.23.5
- pandas 1.5.3
- matplotlib 3.7.0
- seaborn 0.12.2
- sklearn - version 1.2.1
- statsmodels - version 0.13.5



## Contact
Created by [Kushagra007-dev] - feel free to contact me!


