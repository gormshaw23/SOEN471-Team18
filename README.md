# SOEN 471 - Time Series Analysis with Softvie Inc. 

## Abstract 

The main objective of this project is to employ Time Series Analysis to examine and analyze a range of tickets, including Hazard Queries, Incident Queries, and Training data. The output of the analysis will be presented in the form of JSON data, line charts, and graphs/charts. This analysis aims to identify patterns and trends associated with incidents, hazards, and training over time. Such patterns will be looked at on a daily, weekly, monthly and yearly scale. Additionally, the project aims to forecast upcoming Incidents using Time Series Analysis with different machine learning. The results of this analysis will help stakeholders make data-driven decisions and identify areas of improvement.

## Description of the Dataset 

The dataset comprises several schemas, including Employee, General Actions, Incidents, Root Cause Analysis, Submissions, and more. Each schema includes different tables such as Person, Employee, Employee Training, Incidents, Root Cause Analysis, Employees Involved, and Incidents Submissions. For this project, a thorough examination of each table is required to identify the most relevant features for forecasting future hazards. The dataset's wide variety of schemas and tables offer a wealth of information that can help in creating accurate predictions and identifying actionable insights. However, due to the nature of our research questions (see below) the Incident Schema will be our main focus.

## Research Questions 

1. Based on Hazards of previous Days/Weeks/Months/Years (i.e the past) , can we predict the number of the upcoming hazards?

2. If so, which type of data (Days/Months etc) gives the most accurate results.

3. Is there any correlation between an employee’s training time and probability of a hazard?

## Model + Algorithms used on the dataset 

 ### Time Series Analysis 

**Random Forest** is an ensemble learning algorithm that can capture complex relationships between input variables and the output variable over time, making it well-suited for time series analysis of workplace hazards. By using multiple decision trees and random subsets of input variables, Random Forest can model the interactions between factors such as seasonality, trends, and other environmental factors and the number of hazards over time. This provides a robust and accurate forecast of future hazards.

**Seasonal Autoregressive Integrated Moving Average (SARIMA)** is a great fit for analyzing the time series of workplace hazards because it is a univariate forecasting algorithm that can handle our non-stationary data that has white noise, trends and seasonality. SARIMA uses levels (parameter d) of differencing to remove trend and seasonality on the time series to make it stationary.  Once a stationary time series is obtained, SARIMA applies and plots a partial autocorrelation function to get the autoregressive term (parameter p), and a correlation function to get the moving average term (parameter q) and the number (parameter s) of observations in a seasonal period. 


## Team Members 

- Shawn Gorman 40157925
- Samaninder Singh 40133493
- Mahery Ranaivoarison 40005568
- Waleed Afandi 40243372






