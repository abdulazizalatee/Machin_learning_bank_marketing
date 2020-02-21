# Capstone Project 

### Project Objective

The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.

Since the data holds label we will use supervised learning.

The dataset for this project originates from the UCI Machine Learning Repository

### Classification goal
The classification goal is to predict if the client will subscribe (yes/no) a term deposit (output).

### Data Descriptions

age : Age of client: numerical value

job	: Type of job: admin., blue-collar, entrepreneur, housemaid, management,retired, self-employed, services,student,technician, unemployed, unknown

marital : Marital status: divorced, married, single, unknown

education : Level of education: primary, secondary, tertiary, unknown

default : Has credit in default: no, yes, unknown

balance : Average yearly balance in Euro: numerical value

housing : Has housing loan: no, yes, unknown

loan : Has personal loan: no, yes, unknown

contact : Communication type: unknown, telephone, cellular

day : Day of the month: numerical value between 1 and 31

month : Month of the year: jan, feb, mar, apr, may, jun, jul, aug, sep, oct, nov, dec

duration : Last contact duration: numerical value in seconds

campaign : Number of contacts made: numerical value

pdays : Number of days passed since client was last contacted from a previous campaign: numerical value, -1 indicates client was not previously contacted

output : Predictor class: yes, no

### Required Packages

* Pandas
* matplotlib
* numpy
* DecisionTreeClassifier
* GridSearchCV
* train_test_split
* accuracy_score
* metrics


[Project Notebook: Capstone Project](https://github.com/abdulazizatty/Capstone/blob/master/Capstone.ipynb)

[Dataset resource](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing#)

[Blog Post: Understanding Customer Churning with Big Data Analytics](https://medium.com/@bowenchen/understanding-customer-churning-with-big-data-analytics-70ce4eb17669)

