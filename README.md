# Home-Credit-Default-Risk
The goal of this project is to predict the capability of a client to return a loan..
  Fot this I use a dataset from Kaggle of the Home Credit Group -> https://www.kaggle.com/competitions/home-credit-default-risk/leaderboard
The project begins with a short DEA of the Dataframes. Then, I make a function which does the whole feature Engineering part
in one step (previsouly defining the auxiliary functions logically....). Lastly, once I got both train and test Dataframes proccesed, I
started with the Training and Predicting part. In this particular project I select 3 models: A logistic Regression, a Random Forest Classifier
and a LightGMBmodel. The last two models were also train with a RandomSearchCV class in order to get a better result on the competition... you 
can see by yourself the differences. 

