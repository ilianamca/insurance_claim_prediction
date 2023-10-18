# project4
We used a data set containing individuals’  age, sex, weight, bmi, number of dependents, smoker, blood pressure, diabetic status, exercise frequency, and claim price to train machine learning models to predict if a person will have a low, medium-low, medium-high, or high claim price. We ran 4 models, each with varying accuracy: Linear Regression, Random Forest, Decision Tree, and Logistic Regression. 

The linear regression model gave us our lowest accuracy, with a score of 71%. From this model, there is a clear distinction between the charges that smokers have to pay. Age also plays a high role in predicting insurance claims.

The random forest model has great performance. It has a high accuracy of 97.86% and strong precision, recall, and F1 scores across all claim bins. It is particularly great at classifying “medium-high” and “low” claim instances. According to this model, A person’s age and whether or not they are a smoker are the two greatest indicators when predicting a claim.

The decision tree model also has a very high accuracy, of 97%. Making it a very good model to test this dataset against. 

This logisitc regression model has an accuracy of 91%. Making it a very good model to test this dataset against. 
