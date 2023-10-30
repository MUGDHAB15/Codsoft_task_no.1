# Codsoft_task_no.1
Titanic Survival Prediction

Objective:
Use the Titanic dataset to build a model that predicts whether a
passenger on the Titanic survived or not. This is a classic beginner
project with readily available data. The dataset typically used for this project contains information
about individual passengers, such as their age, gender, ticket
class, fare, cabin, and whether or not they survived.

Higlights:

In this Project we are going through the Popular Titanic Data set and predicting whether or not the person survived in the shipwrek. We will be using the Logistic regression model to train our data and make predictions, and then use cross_val_score to check the accuracy of our accuracy score. We will use train_test_split from Sklearn module to split the given data set into test data and train data and use 70 - 30 distribution for our models

Insights:
We have total of 418 rows of data and 12 columns of type integer, object and float64 to work with.
We have 3 columns which have missing values: Cabin , Age and Fare
There are total 418 passengers in a our given data set
Since the survived column has discrete data, the mean gives us the number of people survived from 418 i.e. 36%
Most of the passengers belonged to Pclass = 3
Maximum fare paid for a ticket was 512 however the fare price varied a lot as the standard deviation is of 55.84%
Out of 418 passengers 266 passengers did not survive and 152 survived
Male passengers are more in our dataset
Survival percentage of female passengers is more
Number of people in the 3rd class is more, followed by 1st class, and least number of people are in 2nd class
maximum passengers embarked from 'S' i.e. Southhampton
It seems that the passengers that embarked from port Queenstown had a higher rate of Survival at 53%. This could be either due to their Sex or socio-economic class
'Survived' column is the Target and rest of the column are called 'Features'. We seperate the Feature and the target to move ahead in analysis and we are dropping few columns like Name, Ticket and PassengerId.
We split the dataset into train and test data
We use Logistic regression model and find the accuracy score on a test data set.
We get 100 percentage of accuracy which is really great. However this can rarely be a case in real scenarios as our data must be considered overfitted
In future we can use other models as well to see which model performs best on our dataset.

Thanks.


