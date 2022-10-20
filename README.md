# BE_ML_Project

<h2> Gradient Boosting Regression Trees </h2> 

In this project we have implemented the Gradient Boosting machine learning algorithm.
It works on the principle that many weak learners(eg: shallow trees) can together make a more accurate predictor.
Gradient boosting works by building simpler (weak) prediction models sequentially where each model tries to predict the error left over by the previous model.

The dataset used is California Housing Prices dataset which was imported from the scikit-learn datasets.
The data pertains to the houses found in a given California district and some summary stats about them based on the 1990 census data.

**Data Set Characteristics**

    Number of Instances: 20640

    Number of Attributes: 8 numeric, predictive attributes and the target

    Attribute Information:
        - MedInc        median income in block group
        - HouseAge      median house age in block group
        - AveRooms      average number of rooms per household
        - AveBedrms     average number of bedrooms per household
        - Population    block group population
        - AveOccup      average number of household members
        - Latitude      block group latitude
        - Longitude     block group longitude

    Missing Attribute Values: None

    Target:
      - MedHouseVal     median house value in block group
      
The method used for evaluation of the predictions is mean absolute error.
