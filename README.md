# Logistic_Regression_on_HR_Attrition_data
Implementation of logistic regression model on HR-Attrition data set for prediction of attrition of employees
The repository contains a HR-Employee-attrition data set. The following processes are performed on the data
  1. Studied the nature of data, removed unwanted and irrelevant features
  2. Analyzed relationship between features, ignored independent features showed high correlation with each other
  3. Checked for missing values/unwanted symbols and spaces in data, replaced with corrected values
  4. Checked for outlier values, replaced those with upper/lower limit values.
  5. Converted the categorical variables to numerical using one-hot encoding
  6. Split the data set into x (target feature) and y(input features)
  7. Calculated variance inflation factor (VIF), removed features with VIF>10
  8. split data into train and test data sets
  9. Imported regression model, trained it using train data set
  10. Predicted the test data using trained model, printed confusion matrix and calculated accuracy  
