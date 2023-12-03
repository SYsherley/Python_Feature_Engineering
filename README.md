# Feature engineering 
Feature engineering is one of the keys to unlock predictive insight through mathematical modeling. Based on the data that is available and was cleaned, I identified drivers of churn for the client and build those features to later use in my model.

First, I built on top of the feature: “the difference between off-peak prices in December and January the preceding year”. 

Then, I trained a Random Forest classifier to predict customer churn.

After that, I evaluated the performance of the model with evaluation metrics. 

The hypotheses under consideration is that churn is driven by the customers’ price sensitivities and that it would be possible to predict customers likely to churn using a predictive model.
