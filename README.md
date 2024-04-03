# House Price Prediction



## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularization in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

-   Which variables are significant in predicting the price of a house, and
    
-   How well those variables describe the price of a house.
    

Also, determine the optimal value of lambda for ridge and lasso regression.

**Business Goal** 

You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
1. The 5 most important features in the Original Lasso Model are: 'GrLivArea', ‘MSZoning_FV’, ‘MSSubClass_160’,’Exterior1st_BrkComm’, and ‘AgeofProperty’
2. The 5 most important features in the New Lasso Model are: 'Neighborhood_IDOTRR', 'Neighborhood_MeadowV', 'Neighborhood_OldTown', 'Neighborhood_BrDale', and 'Exterior2nd_Brk Cmn'.
3. The top 10 predictor variables for Ridge Regression are as follows:
- 'GrLivArea'
- 'AgeofProperty'
- 'OverallQual'
- 'MSZoning_FV'
- 'MSSubClass_160'
- 'MSZoning_RL'
- 'Neighborhood_Crawfor'
- 'OverallCond'
- 'MSSubClass_70'
- 'TotalBsmtSF'
4. The top 10 predictor variables for Lasso Regression are as follows:
- 'GrLivArea'
- 'AgeofProperty'
- 'MSZoning_FV'
- 'MSSubClass_160'
- 'OverallQual'
- 'Neighborhood_Crawfor'
- 'MSZoning_RL'
- 'MSSubClass_70'
- 'OverallCond'
- 'MSSubClass_90'

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- python - version 3.7.6
- seaborn - version 0.12.2
- matplotlib - version 3.1.3
- plotly - version 5.18.0
- numpy - version 1.18.1
- pandas - version 1.0.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
