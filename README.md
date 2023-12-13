ML project 2 - vehicle price prediction


Problem type - regression problem

Softwares used - python 3.10, numpy, pandas, matplotlib, sklearn
Editors used - jupyter notebook
In this project we are going to find vehicle prices.

Steps
Step 1 : loading data
Step 2 : cleaning data
Step 3 : training the algorithm
Step 4 : testing the algorithm
Step 5 : Improvising
In this project we have loaded vehicle data using pandas read_csv() function
Vehicle data contains engine capacity, mileage, horse power, etc.
We are going to predict vehicle price based on above features.

Step 1 : loading data
a. We have removed NAN values either by using dropna() function or fillna() function.
b. We have converted text data to number data using dictionary mapping technique.
c. We have removed unwanted columns (the columns which are not deciding factors for price prediction)

Step 2 : clean the data
a. We have spit the data into 70% and 30% proportion for training and testing
b. For splitting the data we have used train_test_split() function
c. We have tried 3 different algorithms for this project, linear regression algorithm, lasso algorithm, and ridge algorithm.
d. For training the algorithm we have used fit() function


Step 3 : train the algorithm
a. We have tested the algorithm with 30% of data by using predict() function.
b. We can find the accuracy of an algorithm by using score() function.
c. We can also find the error of the algorithm using mse() function, which is mean squared error.
d. We have to choose the algorithm whose error is less and accuracy is more.
e. In our project ridge algorithm has given 82% accuracy and error is 2200 dollars. 
f. Error 2200 dollars says, on the algorithm predicted price actual price may differ with 2200 dollars either positive or negative.

Step 4 : testing the algorithm

Step 5 - improvising and conclusion. We have improvised the ridge algorithm by applying alpha tuning parameter.
We are suggesting ridge algorithm for this project.
