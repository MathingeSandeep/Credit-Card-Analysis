# Credit Card Customer Behavior & Revenue Analysis                                                                                                              
Credit Card Analysis Power BI Dashboard

This project presents an end-to-end data analysis using Power BI on a credit card transaction dataset. The goal is to uncover valuable business insights regarding customer behavior, revenue contribution, spending trends, and credit product performance across different segments.

## Tools & Technologies Used

- Power BI Desktop – Visualization and dashboard development

- Power Query Editor – Data transformation and shaping

- DAX (Data Analysis Expressions) – Custom calculations, KPIs

- PostgreSQL – Data querying, importing

- Excel – Source format used for data extraction & preview

## Dataset Description

  Includes details like:

- Card Category (Blue, Gold, Silver, Platinum)

- Customer Demographics (Age, Gender, Education, Marital Status)

- Transaction Metadata (Amount, Revenue, Interest, Quarter, Expenditure Type)

- Customer Job, Income, Use Type (Swipe/Chip/Online)

## Steps Followed

- Data Collection

Received raw dataset in CSV format

- Data Transformation & Cleaning

Used Power Query for additional shaping

Formatted date and time fields

Imported and stored in PostgreSQL

- Data Import into Power BI

Connected PostgreSQL to Power BI via native connector

Loaded cleaned tables for analysis

Created DAX measures (Total Revenue, Interest Earned, Count, CAC)

- Dashboard Creation

Developed two separate dashboards to analyze:

-- Transaction Performance

-- Customer Segmentation & Demographics

## Dashboard 1: Credit Card Transaction Report

### Objective:

Analyze transaction performance across various customer and product segments to assess profitability, channel usage, and revenue drivers.

### KPIs & Visuals:

- Revenue: 57M
- Interest Earned: 7.98M
- Transaction Amount: 46M
- Customer Count: 667K

### Key Visuals:

- Revenue by Card Category
- Quarterly Revenue & Transaction Count
- Revenue by: Education, Customer Job, Expenditure Type, Use Type (Swipe, Chip, Online)
- Customer Acquisition Cost by Card

### Key Insights:

- Blue Card users generate ~83% of total revenue.
- Highest Customer Acquisition Cost(CAC) is for Blue Card (~47M) — high customer value but potentially expensive.
- Bills, Entertainment, and Fuel dominate spending categories.
- Swipe transactions contribute 63% of revenue

## Dashboard 2: Credit Card Customer Report

### Objective:
Understand the customer demographics driving revenue. This includes age, marital status, income levels, and geographical distribution.

### KPIs & Visuals:

- Total Revenue: 57M
- Total Income: 588M
- Average Age: 46
- Average Customer Rating: 3

### Key Visuals:

_ Revenue by: Age Group, Gender, Education Level, Income Group, Marital Status, Dependents
- Top 5 Revenue States
- Revenue by Customer Job
- Weekly Revenue Trends by Gender

### Key Insights:

- Male customers contribute more revenue than female.
- Graduate customers are the top revenue-generating education group.
- High-income customers bring in 40%+ of total revenue.
- Top revenue states: TX, NY, CA, FL, NJ
- Businessmen and White-collar professionals are the most profitable segments.

## Screenshots

- Credit Card Transaction Report
  
![Credit Card Dashboard](https://github.com/user-attachments/assets/b4d3e91d-d8ae-4052-afa1-79069cfc0e35)

- Credit Card Customer Report

![Customer Dashboard](https://github.com/user-attachments/assets/860a1123-0a05-4911-868f-aee8b7654c51)




