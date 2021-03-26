Member:
1. Matthew Brian Darmadi
2. Dante Monaldo
3. Aidan Bossio

Summary: 

For our Neural network model, we decided to go for a Regression model because the question we weretrying to solve and the dataset does not fit in well within the umbrella of 
a “classification” problem.

We decided to tune the parameters and evaluate the models using K-cross validation and RMSE. We alsoanalyzed the R-squared values for test and 
training data. The primary change that we saw tweaking thehyperparameters like alpha was that when alpha was very small the model seemed to overfit the training data.

Hyper-parameters are parameters that are set before the training process begins, while values for the parameter are acquired from the training. 
Also, when testing different hidden layer sizes wedidn’t see a significant difference in performance of the models based on hidden layer size.

For the sake of testing we attempted to change the solver for the model. However, this causedunexpected issues so we chose to remain with the solvar in the examples “lbfgs”.

We don’t see any major differences in the graphed outputs for the different activation functions,but there are some minor variations
