# Covid19-Hospitalization-Prediction
### Title: 
Forecasting future pandemic hospitalization rate by modeling covid-19 pandemic with multiple linear regression, using covid tracking project dataset
### Objective: 
Apply multiple linear regression to COVID-Tracking Project dataset to visualize and compare the prediction trend and the real-time cumulative hospitalization count.
### Methods: 
Using K nearest neighbor to impute the missing datapoints for predicting variables. Dividing the dataset into training set and testing set, then use K-fold cross validation to fit the multiple regression model to the training set. Finally, the model will be used to predict on testing set and compare the prediction results with the real-time cumulative hospitalized count results in the testing set.
### Results: 
The adjusted R-squared value is 0.99 which is very close to 0 which indicates a very strong prediction model is built to do the forecasting. The trend of the cumulative hospitalized count follows with the real-time trend except for New York state. 
### Conclusion: 
The correlation matrix determined strong relationships among outcome variable and predictors. The multiple linear regression model obtained a fairly accurate prediction results for cumulative hospitalized count.
