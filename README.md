# LUXDEV-CAPSTONE-PROJECT-
Introduction
Project Overview
This capstone project focuses on analyzing customer churn for a subscription-based streaming service. Customer churn, defined as the discontinuation of service by subscribers, represents a significant challenge for streaming platforms. By identifying patterns and factors that contribute to churn, the company can develop targeted retention strategies to improve customer lifetime value and reduce acquisition costs.

Business Problem
Streaming services operate in a highly competitive market where customer acquisition costs are substantial. Retaining existing customers is significantly more cost-effective than acquiring new ones. Understanding churn drivers enables the development of proactive retention strategies, personalized engagement tactics, and improved service offerings.
Project Objectives
•	Analyze historical subscriber data to identify patterns and trends related to churn
•	Determine key factors influencing customer churn decisions
•	Create customer segments based on churn risk profiles
•	Recommend actionable retention strategies for different customer segments

Methodology
The technical approach adopted to undertake this project entailed involved the following activities:

Data Pre-processing
The data pre-processing was done using Python language on the Visual Studio Code code editing tool. This included the following steps:
•	Creating a new virtual environment for the project on Visual Studio Code
•	Loading the dataset (csv file) into Python and assigning it a new dataframe name
•	Examining the content and structure of the dataset column by column inorder to identify any early issues with the data
•	Checking for and addressing duplicates and missing values in the dataset
•	Standardizing and normalizing column datatypes as necessary
•	Conducting feature engineering by creating new columns from derived variables


Exploratory Data Analysis
 This involved extracting some preliminary insights from the data that could require some further investigation and included the following tasks:
•	Checking for and addressing outliers from notable columns in the dataset
•	Determining the overall customer churn rate 
•	Conducting correlation analysis to explore relationships between features and churn


Deep Dive Analysis
•	Identifying potential churn risk factors from correlation analysis and creating churn risk profiles for customers based on it
•	Conducting customer segmentation analysis by comparing different variables to the churn risk profiles


Limitations
a)	Unavailability of additional data including Know Your Customer (KYC) information in the dataset that could have allowed more in-depth analysis of trends and patterns related to churn e,g customer location, types of genres watched, number of children.
b)	The dataset contained some discrepancies e.g. some of the records showed  negative total days between join date and last login date .
c)	Lack of adequate time-based data to enable conducting of temporal analysis including trends and patterns


Key Findings
The following were the key insights that were derived from the analysis conducted:
•	The business is operating with a high overall churn rate of 47.4%, meaning that the business has lost almost half of its customer base during the period. 
•	The average viewing duration per customer is approximately 40 hours per month which translates to about 1.3 hours per day. 
•	The low churn risk customer segment had the highest average daily viewing hours per customer (1.8 hours) while the high churn risk customer segment had the lowest average daily viewing hours per customer (1.2 hours).
•	There was a relatively similar average churn rate across all the subscription types offered by the business with Premium(48.6%) ranking highest, followed by Standard(47.4%), Basic(46.9%), and Free Trial(46.5%).
•	There was a relatively similar average churn rate across all the customer age categories with the Youth(49%) ranking highest, followed by Adults(47%) and the Senior Citizens(46%).
•	The customers in the low churn risk category had the lowest average churn rate (38.9%) while the customers in the high churn risk category had the highest average churn rate (48.2%). 
•	The customers with a low number of support tickets (between 0 – 2 tickets) had the highest churn rate (48%) while the customers with a high number of support tickets (between 5 – 6 tickets).
•	There was no significant correlation found between the payment method used by customers and the average churn rate as they were similar across board.
•	Customers that had used the discount offered upon joining the service had a slightly lower average churn rate (45%) compared to those who had not used the discount (50%).
•	Customers who had the auto renewal option enabled had a slightly higher average churn rate (49%) compared to those who had disabled it (46%).


Conclusions
1)	The business has a high customer churn rate of 47.4%. This is indicative of either the current customer retention strategies employed being ineffective or the existence of external factors that are negatively impacting the business’s ability to retain their customers
2)	The average daily viewing hours per customer is approximately 1.3 hours. This usage duration is relatively low and requires further investigation to determine its root causes.
3)	All the subscription type categories had similar average churn rates, showing that none of the subscription plans offered by the business were significantly attractive enough to the customers to retain them long term.
4)	All the customer age categories had similar average churn rates, probably indicative of a one size fits all approach by the business when targeting these customer segments, instead of a more customized approach.
5)	Customers with a low number of support tickets had the highest churn rate (48%) while the customers with a high number of support tickets had the lowest churn rate (33%). Normally, the reverse is true. Further analysis is needed to explain this phenomenon and how it can be addressed.


Recommendations:
1)	The business should provide more data as will be requested by the analyst for further investigation to address some of the concerns and gaps arising from the findings.
2)	A review of the current customer retention strategies by the relevant departments is required to uncover the reasons behind the low service usage by customers, which is likely a key churn risk factor.
3)	The business should consider offering highly customized services to the various customer segments, particularly the subscription type and age category segments to best need their needs.
