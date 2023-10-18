# Insurance Claim Prediction
We used a data set containing individuals’ age, sex, weight, bmi, number of dependents, smoker, blood pressure, diabetic status, exercise frequency, and claim price to train machine learning models to predict if a person will have a low, medium-low, medium-high, or high claim price. We ran 4 models, each with varying accuracy: Linear Regression, Random Forest, Decision Tree, and Logistic Regression. 

For all the models except for Linear Regression, were tested against the bin_claim categories. The claim values were split into quartiles- low, low-medium, medium-high and high claim price. The Linear Regression model was tested against the individual claim prices. 

The linear regression model gave us our lowest accuracy, with a score of 71%. From this model, there is a clear distinction between the charges that smokers have to pay. Age also plays a high role in predicting insurance claims. 

The random forest model has great performance. It has a high accuracy of 97.86% and strong precision, recall, and F1 scores across all claim bins. It is particularly great at classifying “medium-high” and “low” claim instances. According to this model, a person’s age and whether they are a smoker or not are the two greatest indicators when predicting a claim.

The decision tree model also has a very high accuracy, of 97%. Making it a very good model to test this dataset against. Similarly, it is great at predicting the classification of the claim price.
 
This logistic regression model has an accuracy of 91%. Not as precise as the tree models, but still considered a very accurate model. 

Based off the four models we can conclude that the tree models are more accurate compared to the regression models. Tree models are better tests with a more complex data, when we look at our data it’s a mixture of values and variables. When comparing the regression models, there was such a significant difference in the linear and the logistic model. One of the biggest differences is that for the linear model we used the specific claim values to test the accuracy, but for the logistic model, we used the binning price categories. Which would be easier to predict a price range. 
 
