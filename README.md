# Employee Attrition Prediction: Project Overview 
* Created a tool that predicts employee attricion based on 17 employee attributes
* Data is given by lecturer in college, which is a clean sample data of 93 employees
* Decision Tree Classifier is used to reach the model. 
* Decision Tree visualization using scikit learn

## Code and Resources Used 
**Python Version:** 3.7  
**Packages:** pandas, sklearn.

## Attributes
Attributes to predict employees attrition are following:
*	Age
*	Business Travel
*	Department
*	Distance from Home
*	Education Periode 
*	Education Field
*	Environmental Satisfaction
*	Gender
*	Job Role
*	Job Satisfaction 
*	Marital Status
*	Monthly Income
*	Performance Rating
*	Relationship Satisfaction
* Work Life Balance
* Years at Company
* Years at Current Role

## Model Building 

First, I transformed the categorical variables into dummy variables. I also split the data into train and tests sets with a test size of 30%.   

I tried Decision Tree classifier with entropy approach and maximum three dept of 3. I also evaluated them using accuracy rate. I chose decision tree classifier because my goal was to build a simple model that is easy to visualize.

## Model performance
The Decision Tree model performance is presented. 
*	**Decision Tree** : Accuracy = 0.57
The performance is relatively bad because the small data sample and it was imbalanced with the ammount of the attributes.

## Decision Tree Visualization
Decision tree visualization is presented below
![alt text](https://github.com/novaldi21/ds_attrition_project/blob/master/attrition.png "Decision Tree")
