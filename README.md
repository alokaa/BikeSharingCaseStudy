# Bike Sharing Assignment
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

* Which variables are significant in predicting the demand for shared bikes.
* How well those variables describe the bike demands
  
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)



## General Information
- A US bike-sharing provider BoomBikes has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.
- It is required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features.
- The data set is the per-day rental records from 2018-2019. It shows some important fields which potentially affect business like:
  - Date
  - Season
  - Year
  - Month
  - Holiday
  - Weekday flag
  - Working day flag
  - Weather Situation
  - Temperature and Feel Temperature
  - Humidity
  - Wind Speed
  - Count of Casual, Registered and Total rentals.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The final model is 𝑐𝑛𝑡=0.191+0.2341×𝑦𝑟−0.0969×ℎ𝑜𝑙𝑖𝑑𝑎𝑦+0.4782×𝑡𝑒𝑚𝑝−0.1482×𝑤𝑖𝑛𝑑𝑠𝑝𝑒𝑒𝑑+0.0909×𝑚𝑛𝑡ℎ_𝑆𝑒𝑝𝑡𝑒𝑚𝑏𝑒𝑟−0.0551×𝑠𝑒𝑎𝑠𝑜𝑛_𝑠𝑝𝑟𝑖𝑛𝑔+0.061×𝑠𝑒𝑎𝑠𝑜𝑛_𝑠𝑢𝑚𝑚𝑒𝑟+0.0959×𝑠𝑒𝑎𝑠𝑜𝑛_𝑤𝑖𝑛𝑡𝑒𝑟−0.286×𝑤𝑒𝑎𝑡ℎ𝑒𝑟𝑠𝑖𝑡_𝑙𝑖𝑔ℎ𝑡_𝑠𝑛𝑜𝑤−0.0801×𝑤𝑒𝑎𝑡ℎ𝑒𝑟𝑠𝑖𝑡_𝑚𝑖𝑠𝑡𝑦
- The model is a good fit with 10 predictor variables.
- The training data set has a r-squared value of 83%
- p-values are well under the threshold of 0.05 for all variables.
- VIF for all predictor variables are under threshold of 5
- The test data is showing an r-squared value of 80% which is close to training data. This validates that our model is neither an over-fit nor an under-fit.
- All the assumptions of linear regression are validated.


## Technologies Used
- Python 3.12.1
- Jupyter Notebook 6.5.4
- numpy
- pandas
- matplotlib
- seaborn
- scikit learn
- statsmodel



## Contact
Created by [Alok Aparanji](https://github.com/alokaa/) - feel free to contact me!

