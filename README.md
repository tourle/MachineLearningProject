# Read me
## Practical Machine Learning Project
Author: S Haliburton

### Background, dataset and goal of this project
Using wearable devices, it is possible to collect a large amount of data about personal activity relatively inexpensively.
6 participants were asked to perform barbell lifts correctly and incorrectly in 5 different ways.

The goal of this project is to use data from accelerometers on the belt, forearm, arm, and dumbell of the participants to predict the manner in which they did the exercise, ("classe" variable in the training set) using any variables in the data.
More information is available from the website here: http://groupware.les.inf.puc-rio.br/har

Data is read in, cleaned, features created and data split into a training and testing set for cross validation.
Principle components analysis is done to determine the best features for a prediction model, by examining how much of the variance
is explained by each component.
Models of various types are run with various tuning applied and their accuracy is assessed in cross validation against the
testing set.  The out of sample error is determined for each.
A final model is chosen and used against the real test set.
