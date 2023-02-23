# Life_Insurance_Assessement

Question: 'Use this prudential data set to determine the risk factor: https://www.kaggle.com/competitions/prudential-life-insurance-assessmentLinks to an external site..

Apply FOUR different machine learning techniques and evaluate on the test data set and compare their performances. Note that the output variable is an ordinal variable. Hence treat the problem either as a regression problem or convert it to a bunch of binary classification problems. Perhaps two in a group of four try as a regression and the other two try as a binary classification problem but prepare/ETL the data only once. Reduce the dimensionality of the data as needed.'

Downloaded the data and imported it as CSV.
Checked the data and labelled the type of data as categorical or nominal.
Understood the data including the missing data.
Dropped the columns whose null percentage is greater than 30%.
Converted the categorical columns to nominal by using one hot encoding
Reduced the dimensionality of the columns: added all the medical information columns to one
Performed feature selection using Mutual Information
Normalized data using Min-max scaler
Applied Machine Learning models for classification: Logistic Regression, Decision tree, Random Forest, XGBoost Classifier, SVM classifier
Compared the results.
