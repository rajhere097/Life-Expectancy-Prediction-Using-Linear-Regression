For VIF handling I follow this:

I calculated the VIF to check multicollinearity between the independent variables. First, I removed all the columns where the VIF values were above 10. Then, for the columns where the VIF values were above 5, I checked their correlation with the Life Expectancy column. If the correlation was not strong with Life Expectancy, I removed those columns as well.


To create the regression model, I followed these steps:

Imported and cleaned the dataset.

Handled missing values and removed unwanted columns.

Checked multicollinearity using VIF and correlation.

Selected important features for modeling.

Split the data into training and testing sets.

Trained the Linear Regression model.

Predicted life expectancy values.

Evaluated the model using R², Adjusted R², MSE, RMSE, and MAE.

Visualized the results using scatter plots of actual vs predicted values.


Insights : The scatter plot shows that the predicted values are closely aligned with the actual life expectancy values. With an R² score of 0.85, the model explains around 85% of the variance, showing a strong predictive performance.
