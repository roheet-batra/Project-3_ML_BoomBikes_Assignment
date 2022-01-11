## MLR model for the prediction of demand for shared bikes

### <font color = Green > Business Understanding </font>

+ A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. 
+ Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

### <font color = Green > Problem Statement </font>

+ A US bike-sharing provider **BoomBikes** has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. 
+ So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
+ In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. 
+ They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
+ Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
    + **Which variables are significant in predicting the demand for shared bikes.**
    + **How well those variables describe the bike demands**
+ Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

### <font color = Green > Business Goal </font>

+ You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. 
+ They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

### <font color = Green > Steps Followed </font>

1. Reading and Cleaning the Data
2. Understanding the Data
3. EDA
4. Preparing the Data for modelling (tarin-test split, dummy and rescalling etc)
5. Training the model
6. Residual Analysis
7. Predictions and Evaluation on the test set
8. Final Report

### <font color = Green > Potential Causes for the shared bikes demand could be: </font>

1. Time & Season of the year
2. Special Holidays
3. Weather conditions
4. Working day or Non-Working day
5. Ratio of casual vs registered users

**Target variable is cnt: count of total rental bikes including both casual and registered**
