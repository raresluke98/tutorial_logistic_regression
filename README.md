# Logistic Regression

## Aproximattion
For linear regression we approximate the data using a linear function.

f(w,b) = wx + b

y_hat = 1/(1 + e^(-f(w,b)))

### Sigmoid function
s(x) = 1/(1 + e^(-x))

### Cost function
We use the crossentropy function

## Gradient descent
We start at some point on the cost graph and we _iteratively_ update our parameters
(calculate the derivative and go in its direction until we find the global cost minimum)

## Learning rate
Determines how far we go in said direction w/ each step.

## Update rules
w = w - alpha \* dw
b = b - alpha \* db

## FILES:
logistic_regression.py :
Implements the LogisticRegression class with default data, fit and predict methods and the sigmoid activation function.

logistic_regression_tests.py :
Driver program that uses the breast cancer dataset found in the sklearn library and
calculatest the classification accuracy on an 20% random train-test split on the data.

## TODO:
verificat greseala  la 1/1+e^-x
