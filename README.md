# ds1030final
#This is a project used to predict melborune's house sale price based on several features.
#Run the melb_data.csv file for access to data
#I try XGBoost, Lasso Regression, Elastic Net Regression, and Random Forest, and XGBoost has the best performance
#If it takes too long to run the models, try adjust the max_iteration for the imputer 
#I dropped some features to protect personal information (e.g. exact address, agent name)
#I also dropped a few highly correlated features (correlation>0.95) after trying to put them into ML models and received bad performance score & long running time
