# DIAMONDS-PROJECT

# WORKFLOW

In this project, in which I used different models to predict the price of diamonds from a csv given another file with diamonds prices, I follow these steps:

- Obviously, I used a Supervised Learning approach, since I had a list of features (X) and a GT to predict (the price).

- I first analyzed the Dataframe on my TRIALS AND CLEANING jupyter notebook. There I created a new dataframe using the get dummies pandas method, to ocnvert the dataframe in numeric.

- Then I used the results in the notebooks in the folder src with different models: Linear Regression, Random Forest,SGDRegressor and Decission Tree, all of them from sklearn. They are all regression models, since I had to predict prices, not cathegorize them.

# CONCLUSIONS

I have found that the most effective method to predict the price of Diamonds has been using the Random Forest Regressor Model. Thus have been concluded from calculating the r2 score and the mean squared error of every model.