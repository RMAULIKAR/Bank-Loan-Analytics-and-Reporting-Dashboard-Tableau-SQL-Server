# Bank Loan Analytics & Reporting Dashboard — Tableau & SQL Server

##  Project Overview

Built a **three-dashboard Bank Loan Analytics solution** in Tableau using SQL Server as the data source, providing interactive **Summary, Overview, and Details** views for analyzing loan applications, funded amounts, repayments, interest rates, customer segments, and loan performance.

The solution combines KPI tracking, MTD/MoM analysis, time-based trends, geographic analysis, loan segmentation, interactive filters, and detailed loan-level reporting to provide both high-level business insights and granular transaction-level analysis.

---

##  Business Objectives

The dashboard was designed to provide insights into key areas of loan performance, including:

- How many loan applications were received?
- What is the total amount funded?
- How much loan amount has been received back?
- How are loan applications and funding changing over time?
- Which states contribute the highest funded amounts?
- Which loan purposes generate the highest funding?
- How does loan funding vary by employee length?
- What is the distribution of loans across different terms?
- How does funding vary by home ownership?
- What are the key loan-level details and characteristics?

---

#  Dashboard Structure

## 1. Summary Dashboard

The **Summary** view provides a high-level overview of the bank's loan portfolio and overall lending performance.

### Key KPIs

- Total Loan Applications
- Total Funded Amount
- Total Amount Received
- Average Interest Rate
- Average Debt-to-Income (DTI) Ratio

### Performance Analysis

The dashboard provides high-level monitoring of:

- Loan application volume
- Funded loan amounts
- Amount received from loans
- Interest rate performance
- Debt-to-income ratio

MTD and MoM metrics are incorporated into the KPI cards to support period-over-period performance analysis.

---

## 2. Overview Dashboard

The **Overview** dashboard provides detailed analytical views of loan funding patterns across time, geography, customer characteristics, and loan attributes.

### Key Visualizations

####  Time Analysis

- Total Funded Amount by Month
- Monthly loan funding trends
- MTD and MoM performance tracking

####  Geographic Analysis

- Total Funded Amount by State
- State-level comparison of loan funding
- Geographic distribution of lending activity

####  Loan Term Analysis

- Funded Amount by Loan Term
- Comparison between **36-month and 60-month** loan terms

####  Employment Analysis

- Total Funded Amount by Employee Length
- Comparison of funding across different employment durations

####  Loan Purpose Analysis

- Total Funded Amount by Purpose
- Debt consolidation
- Credit card
- Home improvement
- Other
- Small business
- Major purchase
- Car
- Wedding
- Medical
- House
- Moving
- Educational
- Vacation

####  Home Ownership Analysis

Funding distribution across different home ownership categories, including:

- Mortgage
- Rent
- Own

---

## 3. Details Dashboard

The **Details** dashboard provides a detailed loan-level reporting view.

It enables users to drill down from aggregated KPIs into individual loan records.

### Loan-Level Information

The detailed report includes attributes such as:

- Loan ID
- Loan Purpose
- Home Ownership
- Loan Grade
- Sub Grade
- Issue Date
- Installment
- Average Interest Rate
- Loan Amount
- Total Payment

### Interactive Controls

Users can dynamically filter the detailed report using fields such as:

- Purpose
- Address State
- Verification Status
- Grade

A **Select Measure** control allows users to dynamically change the metric being analyzed.

---

#  Key Dashboard Features

## KPI Tracking

The dashboard tracks major lending KPIs including:

- Total Loan Applications
- Total Funded Amount
- Total Amount Received
- Average Interest Rate
- Average DTI

The KPI cards also provide **MTD and MoM comparisons** for monitoring changes in performance.

---

##  MTD & MoM Analysis

Month-to-Date and Month-over-Month calculations are used to compare current performance with previous periods.

This enables analysis of changes in:

- Loan Applications
- Funded Amount
- Amount Received
- Average Interest Rate
- Average DTI

---

##  Interactive Filters

The dashboards provide interactive filtering capabilities, allowing users to analyze loan performance based on different dimensions.

Examples include:

- Loan Purpose
- Address State
- Verification Status
- Loan Grade
- Loan Term
- Home Ownership
- Employee Length

---

##  Interactive Dashboard Navigation

The Tableau solution includes interactive navigation between:

**Summary → Overview → Details**

Users can move between high-level portfolio metrics, analytical visualizations, and detailed loan-level records for seamless exploration.

---

#  Tools & Technologies

| Technology | Usage |
|---|---|
| **SQL Server** | Data storage and data source |
| **SQL** | Data querying and preparation |
| **Tableau** | Data visualization and dashboard development |
| **Tableau Calculations** | KPI and analytical calculations |
| **Interactive Filters** | Dynamic data exploration |
| **Dashboard Actions** | Navigation and interactivity |

---

#  Key Metrics

The dashboard provides metrics such as:

- **Total Loan Applications:** ~38.6K
- **Total Funded Amount:** ~$435.8M
- **Total Amount Received:** ~$473.1M
- **Average Interest Rate:** ~12.0%
- **Average DTI:** ~13.3%

*Values represent the results displayed in the dashboard for the available dataset.*

---

#  Business Insights Enabled

The dashboard enables users to analyze:

- Overall loan application and funding performance.
- Monthly trends in funded loan amounts.
- Geographic distribution of loan funding across U.S. states.
- Funding differences between 36-month and 60-month loan terms.
- Loan funding across different employment lengths.
- Loan purpose-wise funding contribution.
- Funding distribution across home ownership categories.
- Loan-level characteristics including grade, sub-grade, interest rate, installment, and payment amounts.
- Period-over-period changes using MTD and MoM metrics.

---

