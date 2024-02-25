# Logistic_Regression_Model_MachineLearning

## What is Logistic Regression ?

Logistic regression is a statistical method used for binary classification tasks, where the goal is to predict the probability of an observation belonging to one of two classes. It's called "logistic" regression because it models the probability of the response variable (usually denoted as Y) being in a particular category using a logistic function.

In logistic regression, the response variable is categorical with two possible outcomes, often coded as 0 and 1. The predictor variables (also known as independent variables or features) can be continuous, categorical, or a mix of both.

The logistic regression model takes the form of:

## P(Y = 1 | X) = 1 / 1 + e^-(β0 + β1X1 + β2X2 + .......+ βpXp)
 
Where:

P(Y=1∣X) is the probability of the response variable being 1 given the values of the predictor variables.

X1, X2,…, Xp are the predictor variables.

β0 + β1X1 + β2X2 + .......+ βpXp are the coefficients of the logistic regression model, representing the strength and direction of the relationship between the predictor variables and the log-odds of the response variable.

The logistic function, 1 / 1 + e^-z, transforms the linear combination of predictor variables and coefficients into a value between 0 and 1, representing a probability.

Logistic regression is widely used in various fields such as healthcare, finance, marketing, and social sciences for tasks such as predicting customer churn, classifying emails as spam or not spam, predicting the likelihood of a disease based on patient characteristics, etc. It's a popular and powerful tool for binary classification when the relationship between the predictors and the response variable is assumed to be linear in the log-odds.
