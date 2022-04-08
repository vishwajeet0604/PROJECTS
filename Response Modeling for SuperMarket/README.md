#  Project Report -


# Objective of the Project -
Leverage the spend behavior and past campaign responses to build a response model that can
be used to devise a strategy that enhances the response rates and improves profitability of marketing campaigns.

# Algorithms Used :
In this project we have used Logistic Regression, Decision Trees, Random Forests and Gradient Boosting Algorithms

# Final Model Algorithm
Among the models that we tried building the GBM Algorithm performed the best in terms of F1_Score, Area under ROC Curve
and overall Model Gini

Therefore we have kept GBM as the final model algorithm

# Model Performance Measures
Accuracy - 0.88

Precision - 0.75

Recall - 0.28

F1 Score - 0.41

AUC - 0.63

 
 # Top 10 drivers from the Model

- MntMeatProducts
- Income
- AcceptedCmp3_1
- Customer_Tenure_9
- MntFishProducts

# The Best Offers should be provided on the following products
- Wines Products
- Fish Products
- Meat Products
- Gold Products
- NumStorePurchases_2
- Marital_Status_Together
- NumCatalogPurchases_10
- NumCatalogPurchases_6
- NumWebPurchases_7
