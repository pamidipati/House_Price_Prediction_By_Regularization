# House_Price_Prediction_By_Regularization
> This is about building regularization models using Ridge & Lasso for predicting housing prices.


## Table of Contents 
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- Business Objective
                 Build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
Need to odel the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

- Data Set Details  
https://cdn.upgrad.com/UpGrad/temp/87f67e28-c47e-4725-ae3c-111142c7eaba/data_description.txt

- Model Details
                Machine Learning approach is used to model this system.This comes under Regularization model.Below are the steps followed in this approach to model the system.
  - Step 1 : Data understanding and exploration
  - Step 2 : Data cleaning
  - Step 3 : Data preperation
  - Step 4 : Model building and evaluation
 

## Conclusions
After regularization, r2 values of train and test are as below
- Ridge (Train : 0.88 Test:0.85)
- Lasso (Train : 0.87 Test:0.85)

The above r2 value indicates that overfitting value has been resolved.

Among all above mentioned features, following are the top most significant features to predict Sales Price
-GrLivArea
-OverallQual
-GarageCars_3
-FullBath_3l
-Neighborhood_NoRidge (Northridge)
-YearBuilt
-BsmtQual (-ve coeff)

## Technologies Used
Following libraries used
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - sklearn

## Contact
Created by @pamidipati - feel free to contact me!
