# UK-Fintech-Neobank-Analytics-Dashboard-Onyx-DataDNA
A Power BI-based Transaction Intelligence Platform for a UK digital neobank to analyze transaction performance, fraud risk, customer behavior, revenue generation, and channel effectiveness. Designed interactive dashboards featuring executive KPIs, fraud analytics, customer segmentation, regional benchmarking, &amp; financial performance monitoring.

# 📌 Project Overview

Financial institutions process thousands of transactions daily across multiple channels and customer segments. This project was developed to provide a centralized analytics platform that helps stakeholders:

✔ Monitor transaction growth and volume trends
✔ Detect and analyze fraudulent activities
✔ Track declined and reversed transactions
✔ Evaluate customer risk exposure
✔ Measure regional and segment performance
✔ Analyze channel utilization and revenue generation
✔ Support data-driven business decisions

# 🎯 Business Objectives
✔ Transaction Monitoring
✔ Track total transactions and transaction volume
✔ Measure Month-over-Month (MoM) growth
✔ Monitor average transaction values
✔ Fraud & Risk Management
✔ Identify suspicious transaction patterns
✔ Analyze fraud concentration by region
✔ Track customer risk scores
✔ Measure decline and reversal rates
✔ Revenue Analytics
✔ Monitor fee revenue generation
✔ Evaluate international transaction contribution
✔ Analyze channel profitability
✔ Customer Intelligence
✔ Segment customers based on account type
✔ Analyze customer tenure and behavior
✔ Identify high-risk customer groups

# 📊 Dashboard Pages

## 1️⃣ Executive Summary

Provides a high-level view of overall banking performance.

## Key KPIs

✔ Total Transactions
✔ Total Transaction Volume
✔ Average Transaction Value
✔ Fraud Flagged Transactions
✔ Declined & Reversed Transactions
✔ MoM Growth Metrics

## Key Visuals

✔ Monthly Volume Trends
✔ Regional Transaction Distribution
✔ Customer Segment Analysis
✔ Channel Performance Breakdown
✔ Volume Growth Comparison

## Business Insights

✔ Transaction activity increased significantly compared to the previous month.
✔ Fraud incidents grew faster than transaction growth.
✔ Automated and Mobile channels generated the highest transaction volume.

# 2️⃣ Risk & Fraud Analytics

Dedicated page for monitoring operational risk and fraud activity.

## Key KPIs

✔ Decline Rate %
✔ Reversal Rate %
✔ Fraud Share by Region
✔ Customer Risk Score

## Analysis Areas

✔ Fraud Distribution
✔ Regional Risk Profiling
✔ Customer Risk Segmentation
✔ Age Group Analysis
✔ Customer Tenure Analysis

## Risk Indicators

✔ High-risk regions
✔ Fraud concentration trends
✔ Declined transaction patterns
✔ Customer risk exposure

## Business Insights

✔ London contributes the highest share of fraud events.
✔ Multiple regions show elevated risk levels.
✔ Fraud rates exceed industry benchmark ranges.

# 3️⃣ Revenue & Channel Health

Evaluates revenue streams and customer interaction channels.

## Key KPIs

✔ Total Fee Revenue
✔ International Transaction Value
✔ International Fee Contribution
✔ Mobile Transaction Share

## Analysis Areas

✔ Revenue Performance
✔ Channel Utilization
✔ Customer Cohort Analysis
✔ Regional Outperformance Index
✔ Volume vs Risk Severity Matrix

## Business Insights

✔ Mobile banking is the dominant customer channel.
✔ International transactions contribute a significant share of transaction volume.
✔ Fee revenue opportunities remain underutilized.

# 🏗 Data Model

The solution follows a star-schema data model for optimal Power BI performance.

## Fact Table

### Fact Transactions

Transaction ID
Customer ID
Region ID
Channel ID
Segment ID
Transaction Amount
Transaction Date
Transaction Status
Fraud Flag
Fee Revenue

## Dimension Tables

### Dim Customer

Customer ID
Customer Segment
Age Group
Customer Tenure

## Dim Region

Region ID
Region Name

## Dim Channel

Channel Type

## Dim Date

Date
Month
Quarter
Year

# 📈 Key Metrics & KPIs

## Transaction Metrics

✔ Total Transactions
✔ Transaction Volume
✔ Average Transaction Value
✔ Monthly Growth %

## Risk Metrics

✔ Fraud Count
✔ Fraud Rate %
✔ Risk Score
✔ Decline Rate %
✔ Reversal Rate %

## Revenue Metrics

✔ Fee Revenue
✔ International Revenue Share
✔ Channel Contribution

## Customer Metrics

✔ Customer Segmentation
✔ Tenure Distribution
✔ Age Group Analysis

# 🧮 DAX Measures Implemented

## Core Measures

✔ Total Transactions
✔ Total Volume
✔ Average Transaction Value
✔ Fraud Count
✔ Fraud Rate %
✔ Declined Transactions
✔ Reversed Transactions
✔ Fee Revenue

## Advanced Measures

✔ Month-over-Month Growth %
✔ Previous Month Comparison
✔ Regional Contribution %
✔ Channel Share %
✔ Risk Score Calculation

# 🔍 Analytical Features

✔ Fraud Detection Analytics
✔ Fraud concentration analysis
✔ High-risk region identification
✔ Fraud contribution by segment

# Customer Segmentation

✔ Starter Customers
✔ Standard Customers
✔ Premium Customers
✔ Business Customers

## Channel Analytics

✔ Mobile App
✔ Web Browser
✔ ATM Network
✔ Automated Transactions

## Regional Performance Monitoring

✔ London
✔ Midlands
✔ South East
✔ Scotland
✔ North West
✔ Yorkshire
✔ Wales
✔ East of England
✔ North East
✔ South West

# 💡 Key Findings

## Growth Performance

✔ Strong Month-over-Month transaction growth.
✔ Increasing transaction volume across all channels.

## Fraud Trends

✔ Fraud activity represents a significant percentage of total transactions.
✔ London contributes the largest fraud share.

## Customer Behavior

✔ Loyal customers form the largest customer base.
✔ Premium and Business segments generate substantial transaction activity.

## Revenue Performance

✔ International transactions contribute meaningful transaction value.
✔ Mobile banking drives customer engagement.

# 🛠 Tools & Technologies

✔ Power BI Desktop
✔ DAX (Data Analysis Expressions)
✔ Data Modeling
✔ Financial Analytics
✔ Fraud Analytics
✔ Business Intelligence
✔ Data Visualization

# Page 1: Executive Overview
<img width="1455" height="817" alt="01" src="https://github.com/user-attachments/assets/b5ca4baf-a17f-4890-8316-b59bcb9b3456" />

# Page 2: Risk & Fraud
<img width="1454" height="818" alt="02" src="https://github.com/user-attachments/assets/3689b6d2-4481-4c97-bf60-7506e09313d9" />

# Page 3: Revenue & Channels
<img width="1454" height="818" alt="03" src="https://github.com/user-attachments/assets/9aade461-b783-4185-921d-fedc932b2652" />
