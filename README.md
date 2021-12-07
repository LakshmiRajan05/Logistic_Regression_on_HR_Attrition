# Logistic_Regression_on_HR_Attrition_data
Implementation of logistic regression model on HR-Attrition data set for prediction of attrition of employees.
The repository contains a HR-Employee-attrition data set. The following processes are performed on the data.
  1. Study the nature of data, remove unwanted and irrelevant features
  2. Analyse relationship between features, ignore independent features that show high correlation with each other
  3. Check for missing values/unwanted symbols and spaces in data, if present do correction
  4. Check for outlier values, if present replace those with upper/lower limit values.
  5. Convertion of categorical variables to numerical using one-hot encoding
  6. Split the data set into x (target feature) and y(input features)
  7. Calculate variance inflation factor (VIF), remove features with VIF>10
  8. split data into train and test data sets
  9. Import regression model, train it using training data.
  10.Predict the test data using trained model, find confusion matrix and calculate accuracy    
