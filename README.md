# Telecom-Churn-Prediction-Advanced-Machine-learning


## Problem Statement
#### Business problem overview
- In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.

- For many incumbent operators, retaining high profitable customers is the number one business goal.

-  To reduce customer churn, telecom companies need to predict which customers are at high risk of churn.

- In this project, we will analyse customer-level data of a leading telecom firm, build predictive models to identify customers at high risk of churn and identify the main indicators of churn.


#### Definitions of churn
- There are various ways to define churn, such as:

#### Revenue-based churn:
- Customers who have not utilised any revenue-generating facilities such as mobile internet, outgoing calls, SMS etc. over a given period of time. One could also use aggregate metrics such as ‘customers who have generated less than INR 4 per month in total/average/median revenue’.

The main shortcoming of this definition is that there are customers who only receive calls/SMSes from their wage-earning counterparts, i.e. they don’t generate revenue but use the services. For example, many users in rural areas only receive calls from their wage-earning siblings in urban areas.

#### Usage-based churn:
Customers who have not done any usage, either incoming or outgoing - in terms of calls, internet etc. over a period of time.

A potential shortcoming of this definition is that when the customer has stopped using the services for a while, it may be too late to take any corrective actions to retain them. For e.g., if you define churn based on a ‘two-months zero usage’ period, predicting churn could be useless since by that time the customer would have already switched to another operator.

In this project, we will use the usage-based definition to define churn.

#### Objective
-  To Predict the customers who are about to churn from a telecom operator . Business Objective is to predict the High Value Customers only . We need to predict Churn on the basis of Action Period (Churn period data needs to be deleted after labelling) Churn would be based on Usage

#### Requirement:
- Churn Prediction Model . Best Predictor Variables

#### Steps to Approach The Best Solution For This Case Study
There are mainly 6 steps

##### Step 1 :
- Data reading
- Data Understanding
- Data Cleaning
- Imputing missing values

##### Step-2 :
- Need to Filter high value customers

##### Step-3 :
- Derive churn need to Derive the Target Variable

##### Step-4 :
- Data Preparation

- Derived variable
- EDA
-Split data in to train and test sets
- Performing Scaling
##### Step-5 :
- Handle class imbalance
- Dimensionality Reduction using PCA
- Classification models to predict Churn (Use various Models )
##### Step-6 :
- Model Evaluation
- Prepare Model for Predictor variables selection (Prepare multiple models & choose the best one)
- Finally we need to give best Summarize to the company


#### Conclusion :
The best model to predict the churn is observed to be Random Forest based on the accuracy as performance measure.

The incoming calls (with local same operator mobile/other operator mobile/fixed lines, STD or Special) plays a vital role in understanding the possibility of churn. Hence, the operator should focus on incoming calls data and has to provide some kind of special offers to the customers whose incoming calls turning lower.

#### Details:
After cleaning the data, we broadly employed three models as mentioned below including some variations within these models in order to arrive at the best model in each of the cases.

##### Logistic Regression :
Logistic Regression with RFE Logistic regression with PCA Random Forest For each of these models, the summary of performance measures are as follows:

##### Logistic Regression
- Train Accuracy : ~90% 
- Test Accuracy : ~88%

##### Logistic regression with PCA
- Train Accuracy : ~92% 
- Test Accuracy : ~92%

##### Decision Tree with PCA:
- Train Accuracy : ~94% 
- Test Accuracy : ~93%

##### Random Forest with PCA:
- Train Accuracy :~ 92% 
- Test Accuracy :~ 92%

## Technologies Used
Python 3
matplotlib
numpy
Pandas
seaborn
sklearn
statsmodels
imblearn
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Kaggle Link:
https://www.kaggle.com/code/shammikapoor/telecom-churn-prediction-advanced-ml

## Contact
Created by [@shammi1988] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
