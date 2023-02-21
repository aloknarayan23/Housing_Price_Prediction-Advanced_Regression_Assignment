#Housing Price Prediction - Advanced Regression Assignment
A US-based housing company named Surprise Housing has decided to enter the Australian market.
The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)

## General Information
- Problem:
		The company has collected a data set from the sale of houses in Australia.
		The company is looking at prospective properties to buy to enter the market. 
		Need to built a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
		
- Agenda :
		Which variables are significant in predicting the price of a house
		How well those variables describe the price of a house.

- Business Goal
		Model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.
	
- DataSet : 
		train.csv

- Steps Followed : 
		~ Data understanding and exploration
		~ Data cleaning
		~ Data preparation
		~ Model building and evaluation
		~ Observation


## Technologies Used
Language : Python 

Libraries : 
      - pandas (To work with dataset)
      - numpy (Math library)
      - seaborn (Graph library that use matplot in background)
      - matplotlib.pyplot (to plot some parameters in seaborn)
      - warnings (to ignore warnings)
	  - sklearn.model_selection (to split the dataframe into Train and Test, GridSearchCV)
	  - sklearn.preprocessing (Using MinMaxScaler to Rescaling the features)
	  - sklearn.feature_selection (RFE, PolynomialFeatures)
	  - sklearn.linear_model (LinearRegression, Ridge, Lasso)
	  - statsmodels.stats.outliers_influence (Check for the VIF values of the feature variables)
	  - statsmodels.api (Building linear regression model)
	  - sklearn.metrics (R-squared score, mean_squared_error)
	  

## Contact
Created by :
        Alok Narayan(https://github.com/aloknarayan23)
		            - feel free to contact me!