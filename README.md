# Regression-Analysis

This notebook goes through various regression techniques with the use of the [Boston Housing dataset](https://archive.ics.uci.edu/ml/machine-learning-databases/housing/). 

The following research questions were identified in the dataset, and analyses were carried out to answer them; 

 - Do the structural factors such as the number of rooms and age of the house and accessibility factors such as distance to highways and employment centres affect the value of houses?
 - Does the level of air pollution play a role in the price of houses in the Boston area?
 - What type of neighbourhood is more desirable for home buyers?
 - What type of relationship do the predictor variables share with the target? Which features are the most important when predicting house prices?
 - Can the median prices of houses be predicted using regression analysis? Which model performs the best?

### Modelling
A number of regression models were applied to the dataset, and the following accuracy scores were obtained after hyper-parameter tuning; 
|Algorithm |R-Squared  |
|-|--|
| Multiple linear regression |0.735
Polynomial regression|0.854
|CART |0.826
Random Foreset|0.87
|XGBoost |0.893

It was concluded that the **XGBoost model** performed the best in predicing the target, whereas Multiple linear regression performed the worst, which was expected since the MLR assumptions were not fulfilled. 

