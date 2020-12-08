# Forecasting Sales from Walmart retail goods (Predictive model)
Objective: Predict the unit sales of Walmart retail goods at stores in various locations for the next 28-days.
Analysis: Data munging is done, merge all the data and make supervised learning single dataset identified, did time series analysis and featurization of train and test data, performed univariate analysis on the data columns and Imputed missing values.
Models Built: Basic Simple Moving Averages is used and regression models such as random forest, extra trees and lgbm models are used. Lgbm gave the best results. 
Results: Performance error used was Weighted Root Mean Squared Scaled Error (WRMSSE). The lgbm model resulted in score of 0.6157 on private score that would end in top 3% on Kaggle leader board. 
Use-cases: The estimation can help different companies to increase their revenues.The model outcome could help in more actionable operational changes and a better use of marketing budgets for those companies who choose to use data analysis on top of Walmart Analytics data. 


