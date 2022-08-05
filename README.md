# Predict_CreditRisk
Predicting Credit Risk: A machine learning model that attempts to predict whether a loan will be approved or not.

In the Credit Risk Evaluator notebook, lending data is loaded from a CSV file. Two models are created on the data and compared: a logistic regression and a random forest classifier. 

It was predicted that the Logistic Regression model would perform better due to the lack of categorical data.

### Results:

Logistic Regression:
* Training Data Score: 0.9943
* Testing Data Score: 0.9937

Random Forest Classifier:
* Training Data Score: 0.9975
* Testing Data Score: 0.9915

While both the Logistic Regression and Random Forest Classifier models performed well, the Logistic Regression performed better as predicted. This is reflected by the smaller difference between training and testing scores (0.0008 vs 0.0060), and also by the higher testing score (0.9937 vs 0.9915).