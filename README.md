# UPI-Transaction-Analysis-Power-BI-Project
📌 **Project Overview**

This project analyzes UPI transaction data to understand payment patterns, customer behavior, merchant performance, regional usage trends, and fraud risks. Using Power BI and Power Query, the dashboard provides insights into transaction success rates, category performance, user demographics, and fraud distribution to support data-driven financial decisions.

The analysis helps identify high-performing segments, peak transaction times, device preferences, and risk-prone areas within the digital payment ecosystem.


🎯**Business Problem**

UPI platforms generate massive volumes of transactions daily, but without structured analytics it becomes difficult to understand:

Customer transaction patterns

Merchant category performance

Regional payment trends

Transaction success vs failure patterns

Fraud-prone segments

Organizations require an interactive analytical dashboard to monitor performance and detect risks.

🎯 **Project Objectives**

Analyze UPI transaction patterns over time

Identify high performing merchant categories

Understand customer demographics and behavior

Track transaction success and failure rates

Detect fraud-prone regions and transaction types

Support strategic decision making for digital payments

🗂 **Dataset Description**

Attribute	Description

Dataset Type	Simulated UPI Transaction Data

Total Records	~250,000 Transactions

Time Period	1 Year

Granularity	Monthly

Key Dimensions	Date, Age Group, Device, Network, Bank, State, Merchant Category

Key Measures	Transaction Amount, Transaction Status, Fraud Flag

🛠 **Tools & Technologies**

Power BI Desktop – Dashboard creation

Power Query – Data cleaning & transformation

CSV Dataset – Transaction data source

🔄 **Data Cleaning & ETL Process**

The dataset was transformed using Power Query before analysis.

Steps Performed

Data Import
Connected the dataset using the Text/CSV connector.

Header Standardization
Promoted the first row as column headers.

Data Type Conversion

Amount → Decimal

Timestamp → DateTime

Fraud Flag → Boolean

Time Feature Engineering
Extracted Month, Day Name, and Hour from the timestamp.

Success Rate Flag
Created a calculated column:
SUCCESS = 1, FAILURE = 0.

Handling Missing Values
Replaced null values in Bank and Merchant Category with Unknown.

Age Group Sorting
Created a numeric column to properly sort age groups in charts.

Load to Power BI Model
Applied transformations and loaded the cleaned dataset.

📊 **Dashboard Analysis**

1️⃣ **Overview Analysis**

Key insights from overall transaction activity:

250K transactions recorded

₹327.9M total transaction value

P2P transactions dominate (~45%)

Shopping and Grocery drive the highest spending

26–35 age group is the most active user segment

2️⃣ **Category Analysis**

Insights related to merchant categories:

Shopping generates the highest revenue.

Grocery transactions occur frequently but have smaller values.

Weekend spending spikes, especially in shopping.

95% transaction success rate indicates strong system reliability.

3️⃣ **Customer Analysis**

Customer behavior patterns:

Android devices dominate (~75%) usage.

4G networks handle the majority of transactions.

SBI has the highest sender transaction volume.

Peak transaction activity occurs around 4 PM.

26–35 age group contributes the most successful transactions.

4️⃣ **Regional Analysis**

Geographical insights from transaction data:

Maharashtra contributes the highest transaction value.

Maharashtra and Karnataka lead transaction volume.

Karnataka records the highest fraud cases.

Tamil Nadu has the lowest fraud occurrence.

5️⃣ **Risk & Fraud Analysis**

Fraud detection insights:

Overall fraud rate is only 0.2%.

July recorded the highest fraud incidents.

P2P transactions show the highest fraud exposure.

Fraud volume is higher on Android and 4G networks due to larger usage.

📈 **Key Insights**

UPI adoption is high among young working professionals (26–35).

P2P transfers and merchant payments dominate the ecosystem.

Fraud levels remain very low but concentrated in certain regions and transaction types.

Device usage and payment patterns are consistent nationwide.

💡 **Business Recommendations**
Customer Strategy

Target 26–35 age group with personalized financial offers.

Merchant Expansion

Increase partnerships with shopping and grocery merchants.

Fraud Prevention

Strengthen authentication mechanisms for P2P transactions.

Network Optimization

Improve 4G network performance during peak hours.

Regional Strategy

Replicate the high adoption model seen in Maharashtra in other states.

📊 **Dashboard Features**

KPI Cards

Category Analysis

Customer Behavior Analysis

Regional Drill-Through Analysis

Fraud Detection Dashboard

Interactive Filters & Tooltips

📌 **Project Outcome**

This Power BI dashboard enables stakeholders to monitor UPI performance, understand customer behavior, optimize merchant strategies, and detect fraud risks using interactive visual analytics.
