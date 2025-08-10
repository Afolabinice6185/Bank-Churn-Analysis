# Bank-Churn-Analysis
In the competitive Banking industry, customers’ critical evaluation of services shapes their perception of the entire company.

## Problem Statement
The primary objective of this project is to analyze call centre operations to identify key areas for
improvement. By leveraging data analytics, the project aims to enhance both efficiency and
customer satisfaction. Specific objectives include:
1. Total Number of calls on each day over the specified period.
2. Geographical Analysis on received calls.
3. Sentimental Analysis on calls.
4. Call Centre Breakdown
5. The top reasons for calls in relation to inflows of calls
6. Channels breakdown and performance rating

## Cleaning Process
To prepare the dataset for accurate analysis, the following cleaning steps were performed:

Removed Errors – Eliminated invalid or inconsistent records (e.g., negative ages, missing key values).

Removed Duplicates – Ensured each record represented a unique customer.

Formatted Age by Grouping – Categorized customers into groups such as Youth, Young Adult, Adult, and Elderly.

Created New Columns using Conditional Commands:

Churn – Classified customers as Churn or Not Churn.

Credit Score Status – Categorized credit scores as Good, Average, or Poor.

Balance Status – Grouped customers into Silver, Metal, Bronze, Gold, or Other.

Salary Status – Grouped customers as Low, Medium, or High earners.

## Visualization
![![Total Churn Analysis](https://github.com/user-attachments/assets/1045b24d-45ec-48b5-abf0-9b075f6e45b1)
](Total Churn Analysis.jpg)

# Overview
This report provides an analysis of customer churn, focusing on key metrics such as estimated salary, balance, customer demographics, and churn distribution by various attributes. The aim is to identify patterns that can guide retention strategies.

## Metric	Value
Average Estimated Salary	100,356.95

Average Balance	76,830.51

Total Customers	3,736

Total Churned Customers	733

Average Age	40 years



## Visualization
![![Count of Churn by Churn](https://github.com/user-attachments/assets/018b6149-4699-44aa-b80c-fba07323544e)
](Count of Churn by Churn.jpg)

# Churn Rate
733 churned customers out of 3,736 total customers.

Churn Rate: ~19.62%

## Visualization
![![Credit Score Status](https://github.com/user-attachments/assets/f4f0559d-350e-4d16-8221-1ad4205d245e)
](Credit Score Status.jpg)

# Credit score status
Customers with Good credit scores form the largest segment.

Poor credit score customers represent the smallest segment

suggesting possible prior filtering by creditworthiness.

## Visualization
![![Balance Status](https://github.com/user-attachments/assets/cf97b570-ffac-4184-a34f-5cf9f10125f1)
](Balance Status.jpg)

# Churn by Balance Status
Silver status customers form the largest group.

The distribution decreases progressively through Metal, Bronze, Gold, and Other categories.

## Visualization
![![Salary Status](https://github.com/user-attachments/assets/c648bdda-ddef-4a28-ad78-e29f6d9171ae)
](Salary Status.jpg)

# Churn by Salary Status
Medium earners dominate the customer base and churn figures.

Low and High earners are roughly balanced in numbers.

Insight: Medium earners may need tailored retention strategies.









