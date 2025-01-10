# Auto-Insurance-Churn-Dashboard

## Project Overview
This is an Analyical Dashboard that aims to analyze factors that may contribute to Customer Churn at an Auto Insurance company, the insights discovered will be important for limiting customer loss.

## Dataset
The dataset used in this project can be downloaded from kaggle through this link
https://www.kaggle.com/datasets/merishnasuwal/auto-insurance-churn-analysis-dataset/data?select=customer.csv

## Tools used
Power BI

## Steps 
### 1-Import csv files into Power BI

### 2-Data cleaning
- Dropped unimportant columns to reduce memory usage
- Replaced missing values
- Added new column Years_Tenure for further analysis
- Added new column Account_Suspended that tells whether customer account is suspended or not in Customers table base on Suspension_Date in Terminatiion Table
- Performed binning on numerical columns ex:Age,Years_Tenure

### 3-Added tables to data model and created relationships between them

### 4-Built Dashboard which includes:
- Main KPI's like total number of customers and number of lost customers.
- Breaks down customer loss by:
- Presence of a college degree
- Credit Score
- Home Ownership
- Years Tenure
- City
- Age
- Income

### 5-Main Insights
- Customers with no college degree are more likely to suspend their accounts
- Customers with bad credit score are more likely to suspend their accounts
- Customers with don't own a house are more likely to suspend their accounts
- Most of the suspended accounts have been there for less than a year or more than 15 years 
- Dallas, Fortworth, Arlington, Plano and Garland are top 5 cities with highest customer loss
- Most lost customers are between 40-59 years old
- Most lost customers have an income of 50k to 150k
  
