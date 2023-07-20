# Exploratory-Data-Analysis-on-titanic-dataset
In this project we will perform exploratory data analysis on titanic dataset with the help of seaborn and matplotlib

Modules installed:
numpy,pandas,matplotlib,seaborn

steps of project:
Data Cleaning:
Check the null values with the help of heatmap function using seaborn
We will replace the null values with some mean of passenger class column because there is relation between pclass and age
and column cabin have alot of null values so we drop it

EDA:
Check the ratio of survived people with the help countplot graph(sns.countplot)
Check the ratio of survived people and gender with the help countplot graph(sns.countplot)
Check the ratio of survived people and passenger class with the help countplot graph(sns.countplot)
we will check the no. of age of peoples in the ship(by dropping null values)
Graph the count plot using sibsp to check the family members of passenger of the ship

Model Implementation:
We will first convert the categorical values into dummy values and concat wit original dataset
We drop the dummy column of (Q,S) because it convert into some null values i dont know why
Convert the data set into train test split
Implement the logistic regression
Accuracy score is 1.0
              
              
