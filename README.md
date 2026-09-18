# LaranaFinance:Loan-Credit-Risk-Analysis
Data analysis project exploring loan applications, approval performance, Contract type, Loan purpose and business insights, Using Microsoft Excel as the main analysis tool, 
## Project Overview

This project analyses loan application and previous loan application data to understand lending performance, approval behaviour, credit exposure and portfolio risk. The analysis focuses on identifying patterns across contract types, loan purposes, payment types, application amounts, credit amounts and decision outcomes.
The project was completed using Excel.

## Business Objectives

The objective of this project was to analyse the loan portfolio and identify patterns that could support better understanding of lending performance and credit exposure.

The analysis focused on:

- Understanding overall loan application volume
- Measuring approval and refusal performance
- Comparing performance across contract types
- Analysing loan purposes and payment types
- Understanding application and credit amount patterns
- Analysing decision speed
- Identifying high-value credit exposure
- Understanding which areas of the lending business are performing differently
- Producing business insights from the analysis

## Dataset

The project uses two main datasets:

### 1. Loan Application

Contains information relating to current loan applications, including application amounts, credit amounts, contract information and application outcomes.

### 2. Previous Application

Contains information relating to customers' previous loan applications, including previous contract information, loan purpose, payment type and previous application outcomes.

The two datasets were analysed and modelled to support a more structured analysis of loan application performance.

## Data Cleaning

The data was cleaned and prepared before analysis.

The cleaning process included:

- Reviewing the structure of each dataset
- Checking column names and data types
- Identifying missing and null values
- Investigating duplicate records
- Reviewing inconsistent categorical values
- Standardising text fields
- Checking numerical columns for appropriate data types
- Reviewing date fields
- Investigating unusual or unexpected values
- Handling values that were not meaningful for analysis
- Creating consistent categories for analysis
- Validating the cleaned data before modelling

## Data Quality

Data quality checks were performed to improve the reliability of the analysis.

The checks included:

- Missing value assessment
- Duplicate record checks
- Data type validation
- Category consistency checks
- Numerical value checks
- Date validation
- Identification of unusual values
- Validation of relationships between tables
- Review of key columns used for analysis

Where data issues were identified, appropriate cleaning or standardisation steps were applied before the data was used for analysis.

## Data Standardisation

Categorical fields were standardised to ensure that similar values were treated consistently during analysis.

Standardisation included:

- Cleaning inconsistent text values
- Standardising category names
- Removing unnecessary spaces
- Reviewing inconsistent capitalisation
- Creating consistent labels for reporting
- Mapping categories into analytical groups where appropriate

This helped ensure that Pivot Tables, measures and visualisations produced consistent results.


## Data Modelling

A structured data model was created to support analysis and reduce dependency on repeated fields within the fact tables.

The model includes the main application data together with supporting dimension tables such as:

- Contract
- Loan Purpose
- Status
- Payment Type

The model was designed to support filtering, aggregation and analysis across different dimensions of the loan portfolio.

### Data Model

![Loan Credit Risk Data Model](images/data-model.png)

Once you commit the README, GitHub should display your screenshot directly underneath the heading.

STEP 12 — Add your KPI section

Use the KPIs you created during your project:

## Key Performance Indicators

The following KPIs were developed to provide an overview of lending performance:

| KPI | Description |
|---|---|
| Total Applications | Total number of loan applications |
| Approved Applications | Number of approved applications |
| Refused Applications | Number of refused applications |
| Canceled Applications | Number of canceled applications |
| Approval Rate | Percentage of applications that were approved |
| Refusal Rate | Percentage of applications that were refused |
| Total Application Amount | Total value of application amounts |
| Average Application Amount | Average application amount |
| Total Credit Amount | Total value of credit amounts |
| Average Credit Amount | Average credit amount per application |
| Average Annuity | Average annuity value |
| Total Down Payment | Total value of down payments |

## Pivot Table Analysis

Pivot Tables were used to explore loan application performance across different business dimensions.

The analysis included:

- Applications by contract type
- Approval rate by contract type
- Applications by loan purpose
- Approval performance by loan purpose
- Applications by payment type
- Application amount bands
- Credit amount bands
- Decision speed categories
- Total credit exposure
- Average credit amount
- Application outcomes

## Management Loan Analytics Dashboard

The dashboard provides a management-level overview of loan application activity, approval performance and credit exposure.

### Dashboard Preview

![Loan Credit Risk Dashboard](images/loan-dashboard.png)

When you save the README, GitHub should display your dashboard image.

