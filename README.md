
## heart disease prediction model

project idea : Heart diseases are characterized as heterogeneous diseases comprising multiple subtypes. 
Early diagnosis and prognosis of heart disease are essential to facilitate the clinical management of patients. 
In this research, a new computational model for predicting early heart disease is proposed. 

>> importing important libraries 
import numpy as np 
import pandas as pd
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import accuracy_score

>>columns in dataset(303rows, 14cols)

1.age
2.sex	
3.cp	
4.trestbps	
5.chol	
6.fbs	
7.restecg	
8.thalach	
9.exang	
10.oldpeak	
11.slope	
12.ca	
13.thal	
14.target

>>DATASET
heart.csv file taken as a dataset from kaggle
data set was cleaned as no null values present
 

>> training of model 
used logistic regression
>>model evaluation
Accuracy on training data : 0.8512396694214877

Feature extraction
A feature extraction method was performed using Classifier Subset Evaluator by applying a training classification data 
to estimate the accuracy of these subsets for all used classifiers on the dataset and measure the quality of the generated subsets
 in order to evaluate the classification performance after selecting the relevant attributes per classification algorithm

