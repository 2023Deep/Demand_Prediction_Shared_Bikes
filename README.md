# Demand Prediction : Shared Bikes
> BoomMBikes, a US bike-sharing provider, has faced revenue declines due to the pandemic. To recover, they aim to develop a strategic business plan post-lockdown. The company has enlisted a consulting firm to analyze factors influencing shared bike demand in the American market. They seek to identify significant variables predicting demand and assess how well these variables explain bike demands. Using data from meteorological surveys and lifestyle information, BoomBikes aims to position itself for success in the anticipated post-quarantine surge in bike usage.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Business Goal
-   Prepare a ML Model to predict demand for shared bikes with the available independent variables. Establish a relationship to predict how demands vary with       
    different features So that the business leaders can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations.
- Objective/s 
    Find out which variables are significant in predicting the demand for shared bikes.
    How well those variables describe the bike demands
- Summary: Summary of the steps followed is available in the presentation and pdf file

## Conclusions
- Count of Casual users has the highest coefficient and can bring in the most impact for our linear model.
- The top four variables are
    - Count of casual users, weekday_Mon, weekday_Sun, weathersit_Light Snow
- Categorical variables have a low to medium impact on the regression model. Though 9 out of 10 independent variables are categorical in our linearregressionmodel, the 
    highest weightage is associated with Casual variable which is not a categorical variable.
- Sunday and Monday have higher impact on the demand as compared to other categorical variables such as different months and weather_light_Snow


## Technologies Used
- Programming Language/s - Python
- Data Analysis Libraries - Numpy, Pandas
- Data Visualization Libraries - Matplotlib.pyplot, Seaborn
- Machine Learnign Libraries - Scikit-learn, SciPy
