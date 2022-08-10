# Surprise Housing
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.


 

The company wants to know:

Which variables are significant in predicting the price of a house, and

How well those variables describe the price of a house.
Also, determine the optimal value of lambda for ridge and lasso regression.
## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
This is a linear regression model followed by regularization using Ridge and Lasso regression techniques


- What is the business probem that your project is trying to solve?

The requirement is to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. 

- What is the dataset that is being used?
The dataset being used is 


## Conclusions
- Lasso Regression seem to perform well has it has higher accuracy and lower MSE
- As the features are too many, a simple linear regression may very complex so it is necessary to apply regularization techniques
- The top predictors using Ridge Regression were

    Features	
0	GrLivArea	
1	OverallQual_Excellent	
2	GarageCars
3	FullBath	
4	TotRmsAbvGrd

- The top predictors using Lasso Regression were

	Features	
0	GrLivArea	
1	GarageCars	
2	OverallQual_Excellent	
3	OverallQual_Very Good	
4	SaleType_New	


## Technologies Used
- library - version 1.0
- library - version 2.0
- library - version 3.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Upgrad for giving the problem statement to get hands on experience


## Contact
Created by [@shrutich91] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->