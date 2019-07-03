# In App Predictions
-----------------
In this repository is code in which a group I was a part of analysed and modeled the probability that a customer will make a purchase in an app. My groups model ended up being a random forest, but we tested gradient boosted forests as well. 

We were working with 20 G of customer data. This included columns on activities of a user in the app. 

You can find a presentation on this [website](alan-perry.com/projects) if you scroll to the right.

--
### Feature Engineering
We engineered salient variables by cleaning the data, and always considering the label and which variables we already had included. This process is what led to us placing second in a kaggle competition.

--
### Modeling
We considered two different models, random forrest and XGBoost. These two models had identical bias. But Random Forest always had a little bit less variance than XGBoost. Ensembling did not change this relationship.
