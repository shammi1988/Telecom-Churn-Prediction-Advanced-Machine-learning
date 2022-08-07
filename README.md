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

