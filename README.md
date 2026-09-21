# LaranaFinance:Loan-Credit-Risk-Analysis
Data analysis project exploring loan applications, approval performance, Contract type, Loan purpose and business insights, Using Microsoft Excel as the main analysis tool.
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

![image alt](https://github.com/DataDrivenMaryam/LaranaFinance/blob/f527f156db2073b9fb56ed507f4c3f81a8eefe32/Data%20model.jpeg)

Once you commit the README, GitHub should display your screenshot directly underneath the heading.

STEP 12 — Add your KPI section

Use the KPIs you created during your project:

## Key Performance Indicators

The following KPIs were developed to provide an overview of lending performance:

## Key Performance Indicators

The following KPIs were developed to provide an overall view of loan application volume, approval performance, credit exposure, application values and decision performance.

| KPI | Description | Measure |
|---|---|---:|
| **No. of Applications** | Total number of loan applications analysed | **1,000** |
| **Approval Rate** | Percentage of loan applications that were approved | **65%** |
| **Total Applications** | Total number of loan application records in the dataset | **1,000** |
| **Refusal Rate** | Percentage of loan applications that were refused | **18%** |
| **Approved Applications** | Total number of loan applications that received an approval decision | **651** |
| **Total Requested Amount** | Total value of the amounts requested across all loan applications | **$150,211,062** |
| **Refused Applications** | Total number of loan applications that were refused | **181** |
| **Total Credit Amount** | Total value of credit amounts associated with the loan applications | **$169,014,107** |
| **Cancelled Applications** | Total number of loan applications that were cancelled | **148** |
| **Average Credit Amount** | Average credit amount per loan application | **$169,014.11** |
| **Average Annuity** | Average annuity/payment amount across the loan applications | **$11,616.01** |
| **Average Application Amount** | Average amount requested per loan application | **$150,211.06** |
| **Total Down Payment** | Total value of down payments across the loan applications | **$3,346,248** |
| **Average Decision Time** | Average time taken to reach a decision on a loan application | **913 days** |

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

## Key Business Insights

### 1. Consumer Loans Have the Highest Approval Rate

**Observation**  
Consumer loans have a significantly higher approval rate compared with the other contract types.

**Evidence**  
- Consumer loans: **86% approval rate**
- Revolving loans: **43% approval rate**
- Cash loans: **40% approval rate**
- Consumer loans recorded **463 approved applications out of 540 applications**.

**Business Meaning**  
Consumer loans demonstrate the strongest approval performance in the portfolio. This suggests that applicants applying for consumer loans are more frequently meeting the lender's approval criteria.

**Recommendation**  
Management should analyse the characteristics of successful consumer-loan applications and identify whether similar characteristics could improve approval performance in other contract types.

---

### 2. Consumer Loans Have the Highest Application Volume

**Observation**  
Consumer loans account for the largest share of applications.

**Evidence**  
- Consumer loans: **540 applications**
- Cash loans: **356 applications**
- Revolving loans: **104 applications**

Consumer loans represent approximately **54% of the 1,000 applications** analysed.

**Business Meaning**  
Consumer loans are an important part of the lending portfolio because they generate the highest level of customer demand.

**Recommendation**  
Management should continue monitoring consumer-loan demand and investigate the customer and product characteristics contributing to its high application volume.

---

### 3. Cash Loans Have the Highest Number of Cancellations

**Observation**  
Cash loans recorded substantially more cancelled applications than the other contract types.

**Evidence**  
- Cash loans: **126 cancellations**
- Revolving loans: **21 cancellations**
- Consumer loans: **1 cancellation**

The 126 cancellations represent approximately **35% of cash-loan applications**.

**Business Meaning**  
The high cancellation level may indicate potential friction within the cash-loan application journey, changes in customer decisions, eligibility issues or other process-related factors.

**Recommendation**  
Management should investigate the reasons for cash-loan cancellations and identify where customers are dropping out of the application process.

---

### 4. Revolving Loans Have the Lowest Application Volume

**Observation**  
Revolving loans have considerably fewer applications than both cash and consumer loans.

**Evidence**  
- Revolving loans: **104 applications**
- Cash loans: **356 applications**
- Consumer loans: **540 applications**

Revolving loans represent approximately **10.4% of total applications**.

**Business Meaning**  
Revolving loans currently represent a smaller proportion of the lending application portfolio.

**Recommendation**  
Management should analyse customer demand, product awareness, eligibility requirements and rejection patterns to understand the lower application volume.

---

### 5. Cash and Revolving Loans Have Similar Approval Performance

**Observation**  
Cash and revolving loans have relatively similar approval rates despite having different application volumes.

**Evidence**  
- Cash loans: **40% approval rate**
- Revolving loans: **43% approval rate**
- Difference: **3 percentage points**

However, cash loans received **356 applications**, compared with only **104 applications** for revolving loans.

**Business Meaning**  
The lower approval performance is not isolated to cash loans. Both contract types have substantially lower approval rates than consumer loans.

**Recommendation**  
Management should compare rejection reasons, applicant characteristics and loan characteristics across contract types to identify factors contributing to the lower approval rates.

---

### 6. Data Quality Check: Application Statuses Do Not Fully Reconcile

**Observation**  
The total number of applications does not fully reconcile with the approved, refused and cancelled application totals.

**Evidence**  

The Grand Total shows:

| Application Status | Total |
|---|---:|
| Approved | 651 |
| Refused | 181 |
| Cancelled | 148 |
| **Combined Statuses** | **980** |
| **Total Applications** | **1,000** |

The three reported statuses total **980 applications**, leaving **20 applications unaccounted for**.

The same issue appears within consumer loans:

- Refused: **56**
- Approved: **463**
- Cancelled: **1**
- Combined: **520**
- Total applications: **540**

This leaves **20 consumer-loan applications** without a corresponding status in the table.

**Business Meaning**  
The discrepancy may indicate missing, uncategorised or differently defined application statuses. This could affect the interpretation of approval and refusal metrics if the unmatched records are not investigated.

**Recommendation**  
The data should be investigated to determine whether the 20 applications represent missing status values, additional status categories, duplicate records or a transformation issue. The status categories should reconcile to the total application count before the analysis is used for final management decisions.

---

## Summary of Key Findings

| Area | Key Finding |
|---|---|
| Application Volume | Consumer loans have the highest volume with **540 applications** |
| Approval Performance | Consumer loans have the highest approval rate at **86%** |
| Cancellations | Cash loans have the highest cancellations with **126 applications** |
| Lowest Volume | Revolving loans have the lowest volume with **104 applications** |
| Cash vs Revolving | Approval rates are similar at **40% and 43%** respectively |
| Data Quality | **20 applications** cannot be reconciled against the reported status categories |

> **Overall Insight:** Consumer loans demonstrate both the highest application volume and the highest approval rate, while cash loans show a relatively high cancellation level and lower approval performance. Revolving loans have the lowest application volume. A data-quality check also identified 20 applications that do not reconcile with the approved, refused and cancelled totals, highlighting an area that should be investigated before using the status analysis for final management decisions.
### Application Volume
![image alt](https://github.com/DataDrivenMaryam/LaranaFinance/blob/6a2394de6c576ec936bca652019683510e8145a0/Application%20Timiming.jpeg)

The Low application amount band contains the largest number of applications, with 610 out of 1,000 applications (61% of the portfolio).

However, its approval rate is 61%, below the overall portfolio approval rate of 65%.

###  Application Amount Performance

The Medium application amount band records the highest approval rate at 74%, compared with the overall portfolio rate of 65%.

The Very High application amount band has the lowest approval rate at 59% and the highest refusal rate at 41%.

Despite containing only 61 applications, the Very High application amount band contributes £63.25 million in total credit, the highest across the application amount bands.

### Credit Amount Exposure

The Very High credit amount band contains 73 applications but contributes £72.01 million in total credit, representing approximately 43% of total credit exposure.

This indicates that a relatively small number of high-value applications account for a substantial proportion of the portfolio's credit value.

The Very High credit band has a 62% approval rate and 38% refusal rate, compared with the overall approval rate of 65%.

### Medium Credit Performance

The Medium credit amount band records the highest approval rate at 76%.

It contains 271 applications and contributes £46.10 million in total credit.

This represents an 11 percentage-point higher approval rate than the overall portfolio.

### Decision Speed Analysis
![image alt](https://github.com/DataDrivenMaryam/LaranaFinance/blob/998e4b2d2d7cfbd8ef544b3d09ce5b56c8dcde2e/Decision%20speed%20.jpeg)
Very Slow decisions account for 671 applications, representing 67.1% of the dataset.

This category records the highest approval rate at 77%, compared with the overall portfolio approval rate of 65%.

However, this result represents an observed relationship in the dataset and does not establish that longer decision times cause higher approval rates.

### Very Fast Decisions

Very Fast decisions have the lowest approval rate at 26%.

However, this category contains only 19 applications, representing 1.9% of the dataset. Therefore, the result should be interpreted cautiously due to the small sample size.

### Average Credit Exposure by Decision Speed

Moderate decisions have the highest average credit amount at £204,810.85, compared with the overall average of £169,014.11.

Very Fast decisions have the lowest average credit amount at £115,911.95.

This shows that average credit exposure varies across decision-speed categories.

## Business Recommendations

Based on the analysis, the following areas could be considered by management:

- Review application performance across different contract types.
- Monitor high-value credit exposure.
- Investigate differences in approval rates across loan purposes.
- Monitor decision speed and its relationship with application outcomes.
- Use application and credit amount bands to support portfolio monitoring.
- Continue monitoring refusal and approval patterns over time.
