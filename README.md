# Bank Transaction Fraud Detection Dashboard

## Project Overview

The **Bank Transaction Fraud Detection Dashboard** is a Power BI data analytics project designed to analyze bank transaction data and identify potentially suspicious transactions.

The project focuses on transforming and analyzing transaction data to provide a clear overview of transaction activity, suspicious transactions, and potential anomalies through an interactive Power BI dashboard.

The dashboard helps users understand transaction patterns and monitor suspicious activity using key performance indicators and visual analysis.

---

## Project Objectives

* Analyze bank transaction data.
* Identify potentially suspicious or anomalous transactions.
* Calculate the total number of transactions.
* Measure the number of suspicious transactions.
* Calculate the percentage of suspicious transactions.
* Analyze suspicious transactions across different transaction attributes.
* Present fraud-related insights through an interactive Power BI dashboard.
* Create an easy-to-understand dashboard for monitoring transaction activity.

---

## Tools & Technologies

* Power BI
* Power Query – Data cleaning and transformation
* DAX – Measures and calculations
* Data Visualization
* Data Analysis

---

## Dataset

The project uses a bank transaction dataset that was cleaned and prepared for analysis.

The Power BI data model contains a table named:

`Bank Transactions Fraud Cleaned`

The dashboard uses the cleaned transaction data for calculations and visualizations.

---

## Data Preparation

The transaction data was prepared before building the dashboard.

The data preparation process includes:

* Data cleaning
* Data validation
* Removing or handling inconsistent records
* Preparing transaction fields for analysis
* Creating a cleaned dataset for reporting
* Preparing data for fraud and suspicious-transaction analysis

---

## Key KPIs

### Total Transactions

Measures the overall number of transactions available in the cleaned dataset.

### Suspicious Transaction Count

Measures the number of transactions identified as suspicious based on the project's anomaly or fraud identification logic.

### Suspicious Transaction Percentage

Calculates the proportion of suspicious transactions relative to the total transaction volume.

### Suspicious vs Normal Transactions

Provides a comparison between suspicious and normal transaction activity.

---

## Dashboard Analysis

The dashboard provides visual analysis of suspicious transactions using transaction attributes.

### Transaction Channel Analysis

The dashboard analyzes suspicious transaction activity across different transaction channels, helping identify which channels have higher levels of suspicious activity.

### Transaction Type Analysis

Transaction types can be analyzed to understand how suspicious activity varies across different types of banking transactions.

### Anomaly Analysis

The project includes a `Potential Anomaly` field to support the identification and analysis of transactions that may require further investigation.

---

## Key Features

* Interactive Power BI dashboard
* KPI cards for transaction monitoring
* Suspicious transaction analysis
* Suspicious transaction percentage
* Suspicious vs normal transaction comparison
* Channel-based analysis
* Transaction-type analysis
* Potential anomaly identification
* Cleaned and structured transaction dataset

---

## Measures

Important measures used in the dashboard include:

```text
Total Transactions
Suspicious Transaction Count
Suspicious Transaction Percent
Percentage of Suspicious Transaction
```

These measures are used to calculate and display transaction-level fraud indicators in the Power BI report.

---

## Dashboard Workflow

```text
Raw Transaction Data
        ↓
Data Cleaning & Transformation
        ↓
Cleaned Transaction Dataset
        ↓
Fraud / Anomaly Identification
        ↓
DAX Measures
        ↓
Power BI Visualizations
        ↓
Fraud Detection Dashboard
```

---

## Business Use Case

Financial institutions process large volumes of transactions every day. Manually reviewing every transaction can be difficult and time-consuming.

A dashboard such as this can help analysts:

* Monitor transaction volumes
* Identify suspicious transaction patterns
* Compare suspicious and normal activity
* Analyze suspicious activity by channel and transaction type
* Prioritize transactions for further investigation
* Monitor fraud-related indicators through KPIs

The dashboard is intended as an analytical and monitoring tool rather than a standalone fraud-decision system.

---

## Dashboard

Add a screenshot of your Power BI dashboard here:

```markdown
![Bank Transaction Fraud Detection Dashboard](images/dashboard.png)
```

---

## How to Use

1. Download the `.pbix` Power BI file.
2. Open the file using Microsoft Power BI Desktop.
3. Review the dashboard KPIs and visualizations.
4. Use available filters and interactions to analyze transaction activity.
5. Explore suspicious transaction patterns across the available transaction attributes.

---

## Project Structure

```text
Bank-Transaction-Fraud-Detection/
│
├── Bank Transaction Fraud detection.pbix
├── README.md
│
└── images/
    └── dashboard.png
```

---

## Skills Demonstrated

This project demonstrates practical experience in:

* Power BI
* Data Cleaning
* Data Transformation
* DAX
* KPI Development
* Data Visualization
* Exploratory Data Analysis
* Fraud and Anomaly Analysis
* Business Intelligence
* Dashboard Development
* Data-driven Reporting

---

## Author

**Sakshi Patil**

Aspiring Data Analyst | Power BI | Data Analytics
