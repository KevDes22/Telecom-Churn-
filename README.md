# Telecom Customer Churn Analysis: California Q2 2022
## Table of Contents
- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Data Source](#data-source)
- [Tools](#tools)
- [Methodology](#methodology)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Results and Insights](#results-and-insights)
- [Recommendations](#recommendations)
- [Conclusion](#conclusion)
### Project Overview
This project analyzes customer churn for a California-based telecommunications company in Q2 2022, using a dataset of 1,581 customers. The analysis focuses on understanding churn drivers, customer demographics, and revenue patterns to inform retention strategies
### Objectives
- The company faces significant customer churn, threatening its revenue and market share. Without a clear understanding of churn drivers, it struggles to identify at-risk customers and implement effective retention strategies
- This project aims to analyze churn patterns, identify key factors, and provide actionable recommendations to reduce churn and support sustainable growth in a competitive market
### Data Source
The dataset, sourced from Kaggle, contains information on 1,581 customers, including:
-	Customer demographics (ID, gender, age, marital status, city, zip code)
-	Service details (internet type, contract type, streaming services, average monthly data download)
-	Billing information (payment method, total charges, refunds, revenue)
-	Churn status and category (Competitor, Dissatisfaction, Price, Attitude, Other)
 This analysis focuses on the 1,581 customers who churned, as provided in the dataset.
### Tools
- Microsoft Excel: Data cleaning, pivot table analysis, and dashboard cre- ation
### Methodology

1.	Data Collection
- The dataset was collected in a structured table format, capturing customer de- mographics, service usage, billing details, and churn status.
	
2.	Data Cleaning
The following steps were performed:
- Removed duplicate records to ensure data integrity.
-	Corrected data type inconsistencies (e.g., ensured numerical fields like To- tal Charges were formatted correctly).

3.	Data Manipulation
- Aggregated data using pivot tables to summarize metrics such as revenue by age group, churn by category, and contract type distribution.

4. Data Visualization
A dashboard was created in Excel, featuring:
-	Bar chart: Total revenue by age group.
- Pie chart: Churn by category (Competitor, Dissatisfaction, Price, Attitude, Other).
- Table: Revenue and customer count by contract type.
- Line chart: Average monthly data download by internet type

### Exploratory Data Analysis
The dataset of 1,581 churned customers revealed the following insights:
- Gender Distribution: 51% female, 49% male.
- 	Age Groups: The 69-78 age group generated the highest revenue ($676,637.98), while the 79-88 age group contributed the least ($122,359.96).
-  churn Categories: Competitor (48.5%), Dissatisfaction (20.2%), Price (17.8%),
Attitude (11.3%), Other (2.2%).
- contract Type: Month-to-Month contracts dominated (88.5%), generating $2,380,631.79 in revenue, compared to One Year ($820,041.82) and Two Year ($314,943.26).
- Internet Type: Fiber Optic was the most common (77.9%), followed by DSL (12.0%) and Cable (10.0%).
- Payment Method: Bank Withdrawal (74.4%), Credit Card (20.0%), Mailed Check (5.6%).
- Total Revenue: $3,515,616.87, with $2,720,675.80 in total charges, $785,923.56 in long-distance charges, and $11,670 in extra data charges.

### Results and Insights
![results](https://github.com/KevDes22/Telecom-Churn-/blob/main/churnshot.PNG)
- High Churn in Month-to-Month Contracts: Customers on Month-to-Month contracts (88.5%) are more likely to churn, likely due to the flexibility to leave without penalties.
- Competitor-Driven Churn: Nearly half of churn (48.5%) is due to competitors, suggesting aggressive competition in pricing or service quality.
- Age-Based Revenue Patterns: Older customers (60-78) contribute significantly to revenue, indicating a loyal but potentially at-risk segment.
- Fiber Optic Dominance: Most churned customers used Fiber Optic (77.9%), which may reflect higher expectations or issues with service quality.

### Recommendations
- Enhance Month-to-Month Retention: Offer incentives (e.g., discounts, loyalty rewards) to encourage longer-term contracts.
- Competitive Analysis: Conduct market research to understand competitor offerings and improve service quality or pricing.
- Targeted Retention for Older Customers: Develop personalized retention strategies for the 60-78 age group, such as tailored promotions or en- hanced support.
-	Fiber Optic Service Improvements: Investigate service quality issues for Fiber Optic users to reduce churn due to dissatisfaction.
 
### Conclusion
This analysis highlights that Month-to-Month contracts and competitor actions are the primary drivers of churn. By focusing on retention strategies for flexible contract holders and improving service quality, the company can reduce churn, retain high-value customers, and enhance long-term profitability. The dash- board provides a clear visual representation of these insights, enabling data- driven decision-making.




