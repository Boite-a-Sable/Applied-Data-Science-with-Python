# Applied-Data-Science-with-Python
This repository is a portfolio of my programming assignments from the Coursera Applied Data Science with Python specialisation by the University of Michigan.

Out of the 6 online courses I have worked through so far, this is the only one that requires a significant amount of independent coding throughout the course and is an excellent place to start learning about data science.

Note that the python library versions of the online Jupyter notebook system are out of date and the autograder is 
temperamental so some answers have been edited to deal with this. The original assignments were written in PyCharm using the most recent libraries then transferred to the Coursera Jupyter notebooks for grading. 

The Courses in this specialisation were:
* Course 1: Introduction to Data Science in Python
* Course 2: Applied Plotting, Charting & Data Representation in Python
* Course 3: Applied Machine Learning in Python
* Course 4: Applied Text Mining in Python
* Course 5: Applied Social Network Analysis in Python

### Course 1: Introduction to Data Science in Python
Covered the basics of python for data science, the pandas library and statistical data analysis using SciPy.stats
* [Assignment W2: Pandas and Numpy](./C1_W2_Assignment.ipynb) 
Part 1: Exploratory data analysis using Pandas on olympic medal data extracted from Wikipedia. Part 2: Use aggregating (groupby) to explore US census state and county data.
* [Assignment W3: Advanced Pandas](./C1_W3_Assignment.ipynb) 
Data cleaning and advanced Pandas. In the initial part of this exercise I cleaned, joined and reduced three datasets before exploring the data and investigating the summary statistics and correlations.
* [Assignment W4: Hypothesis Testing](./C1_W4_Assignment.ipynb) 
Hypothesis testing looking at the effect of the 2008 recession on house prices in university towns. three datasets were cleaned and merged. The recession start, length and bottom were found from timeseries GDP data and finally a t-test was performed to test the hypothesis "University town house prices are less affected by a recession"

### Course 2: Applied Plotting, Charting & Data Representation in Python
This course covered ethics and theory of data visualisation for data scientists. What makes a good visualisation and how to tailor data appropriately for the intended audience. The course then moved onto plotting in matplotlib.
* [Assignment W2: Plotting Weather Patterns](./C2_W2_Assignment.ipynb) 
I was in familiar territory in the assignment going back to my days as a weather scientist at the UK Met Office. The task was to average climate time series data over a ten year period then plot days on which the average 10 year max/min temperatures were exceeded in the subsequent year and present the data in an attractive visualisation.
* [Assignment W3: Custom Visualisation](./C2_W3_Assignment.ipynb) 
In this assignment I build an interactive bar chart which allowed the user to click a y value on the chart. This would change the colour of the bar plots depending on whether the selected y value was above, below or within the confidence level for each bar. 
* [Assignment W4: Becoming an Independent Data Scientist](./C2_W4_Assignment.ipynb) 
In this assignment we were given a wide scope to explore a topic of interest to us. I chose to use this as a data cleaning exercise and extracted 6 sets of data from Wikipedia about the Original Six NHL ice hockey teams. After cleaning and standardising the data sets I selected and created the features I wanted to investigate. The final visualisation looked at the rolling average over the end of season points since 1926 and provided a probability denisty plot of the finishing position for each team over the period.


### Course 3: Applied Machine Learning in Python
This course covered the fundamentals of machine learning: supervised and unsupervised learning; model evaluation and metrics; feature selection and hyperparameter tuning (GridSearch); and application using Scikit Learn.
* [Assignment W1: Basic of ML](./C3_W1_Assignment.ipynb) 
Using the Wisconsin Breast Cancer Data Set this assignment taught me to prepare train and test sets then fit a kNN classifier in sk-learn. Finally the model was used to predict and evaluate data from the test set. 
* [Assignment W2: Supervised ML](./C3_W2_Assignment.ipynb) 
Part 1: Covered the various regression techniques and their evaluation and selection. Part 2: Classification using the UCI Mushroom Data Set. Created dummy variables; applied decision trees and support vector classifiers; and used validation curve to optimise the gamma parameter (kernel width).
* [Assignment W3: Evaluation](./C3_W3_Assignment.ipynb)
Using the Kaggle Fraud Data Set looked at a number of ways to evaluate and optimise a classifier including comparison with a dummy classifier; accuracy, precision-recall curves and ROC curve; and using GridSearch to find the optimimum parameters for logistic regression. 
* [Assignment W4: Supervised ML 2](./C3_W4_Assignment.ipynb)
Given a data set for blight violations in Detroit we were allowed to use any approach to predict payment of fines on an undisclosed test set. I used feature selection and GridSearch on a random forest to produce a ROC AUC score of 0.79

### Course 4: Applied Text Mining in Python
* [Assignment W1:](./C4_W1_Assignment.ipynb)
* [Assignment W2:](./C4_W2_Assignment.ipynb)
* [Assignment W3:](./C4_W3_Assignment.ipynb)
* [Assignment W4:](./C4_W4_Assignment.ipynb)

### Course 5: Applied Social Network Analysis in Python
* [Assignment W1:](./C5_W1_Assignment.ipynb)
* [Assignment W2:](./C5_W2_Assignment.ipynb)
* [Assignment W3:](./C5_W3_Assignment.ipynb)
* [Assignment W4:](./C5_W4_Assignment.ipynb)
