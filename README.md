# Telecom_Churn_Prediction_Case_Study_Anu_Shilpa

## Problem Statement

In the telecommunication industry, customers tend to change operators if not provided with attractive schemes and offers. It is very important for any telecom operator to prevent the present customers from churning to other operators. The aim of the case study is to build an ML model which can predict if the customer will churn or not in a particular month based on the past data.

## Steps To Be Followed¶

**Analyze data-set** - As part of exploratory data analysis activity, the dataset is read and understood. Missing values are handled and outlier treatment is done for the data set.

**Data Visualization** - Check the target variable churn probability against other parameters using Univariate & Bivariate analysis.

**Data Preparation** - Train & test data sets are built for model selection based on the test data set provided.

**Model Selection & Model Building/Evaluation** - There are various models built for evaluation using, PCA with logistic regression, PCA and logistic regression using cross validation, PCA & Random forest. Hyperparameter tuning has been taken care.
                                                  
**Choose Best Model & Important Features** - Based on the analysis of the various models built from the above steps, we will choose the best model & their important features.

# Conclusion

As per our univariate analysis,
- The maximum churn happens during the first 6 months. Hence the focus should be more on those customers.
- The customers with lower outgoing calls during August are the higher risk and hence those customers should be focused on.

By checking the average revenue per user the churn probability is lower. So, those customers must be concentrated upon.

The roaming usage incoming and outgoing calls seems to be the prime predictors of churn. Company can plan stratergies of lowering rates for roaming usage accordingly.

The local incoming calls within same operator is the another important predictor of being churn and company can plan retention stratergy accordingly.

The total recharge plan amount is also one of the best indicator of churn probability and company can provide discount plans on recharge.
