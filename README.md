# My_Portfolio
Example data science portfolio

## [Project 1: Predicting the correctness of exercise performance](https://github.com/nravinskaya/practicalMachineLearning)

This is my course project for **"Practical Machine Learning"** course authorized by Johns Hopkins University and offered through Coursera.

The goal of this project is to predict how people performed the exercise based on data about personal movement that were collected from accelerometers on the arm, belt, dumbbell, and forearm when lifting the barbell.  
The dataset was collected from 6 participants. They were asked to perform barbell lifts correctly and incorrectly in 5 different ways - these are 5 values of the "classe" variable in the training dataset.  
I also have the test dataset (without "classe" variable) to predict the correctness of exercise performance in 20 different test cases using my best model.

The report focuses on:

- cleaning and preprocessing data
- building several machine learning models  
- performing for each model
    * cross validation  
    * model evaluation
- choosing the best model
- making prediction

**Results**

I built four models: two for each algorithm **random forest** and **decision tree**, using the packages `caret`, `randomForest` and `rpart`.  
Based on the results of the accuracy assessment, the first of the considered models was selected to complete the final test. 

[View full report](https://nravinskaya.github.io/practicalMachineLearning/index.html)

