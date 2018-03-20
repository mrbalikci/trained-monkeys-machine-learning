# Machine Learning 

# Trained Monkeys #

## Description 

Keywords: linear regression, nonparametric regression

## Description

Some handicapped people have access to trained monkey helpers that can perform household tasks like switching things on and off. This data set gives the number of tasks each of nine monkeys can perform along with the number of years the monkeys have been working with handicapped people.

Variable: Description
Name: Name of monkey
Years: Number of years the monkey has worked with handicapped people
Tasks: Number of tasks the monkey can perform

## Source

Journal of Rehabilitation Research and Development 28, No.2, Spring 1991, pages 91-96.

## Hypothesis

The number of years that a monkey has worked is a predictor for the number of tasks that the monkey can perform

## Method Used 
* Least Squares 
* R-squared and Mean Squared Error for validity

## Data Set 
* monkeys.csv

## Tools Used 
* Python
* Pandas
* Numpy
* Sklearn
* Matplotlib

## Conclution

MSE score would make more sense if the data is normalized 
R-squared value is here less than 0.5 so the model is not that strong. 
If the outliers were cleaned the prediction equation would make more sense.
