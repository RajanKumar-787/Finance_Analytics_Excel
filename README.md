# Finance Analytics Excel

This project is part of the Codebasics Data Analytics Bootcamp, where I used Excel to analyze the P&L statements and deliver actionable insights through dynamic and interactive reports.

## Table of Contents
- [Project Overview](#project-overview)
- [Tech Stack](#tech-stack)
- [Dataset](#dataset)
- [Data Model Overview](#data-model-overview)
- [Excel Reports](#excel-reports)
- [Key Insights](#key-insights)
- [Author & Contact](#author--contact)

## Project Overview
This Excel project analyzes AtliQ Hardware's Profit and Loss statements from FY 2019 to FY 2021. AtliQ Hardware is a leading computer hardware company that sells its products through various channels including retail stores, direct sales, and distributors. 

The project focuses on Net Sales, Cost of Goods Sold (COGS), Gross Margin, and Gross Margin % (GM%) to evaluate the company's financial health, support data-driven decisions for future growth, and facilitate effective communication with stakeholders.

## Tech Stack
- **Microsoft Excel**
  - Power Query (ETL — Extract, Transform, Load)
  - PivotTable
  - Power Pivot
  - Data Modelling (Star Schema)
  - DAX (Data Analysis Expressions)
  - Conditional Formatting

## Dataset
The dataset used in this project is provided for learning purposes as part of the course and is not publicly shared on GitHub due to course policy.

## Data Model Overview

This data model follows a star schema design with:
- **Fact Table:** `fact_sales_monthly`
- **Dimension Tables:** `dim_customer`, `dim_product`, `dim_market`, `dim_date`
- **Relationships:** Properly established one-to-many relationship for accurate aggregation and reliable reporting

![Data Model](https://github.com/RajanKumar-787/Finance_Analytics_Excel/blob/356e63c4a615ce00b704114e2388e7d7a186d939/Images/Data%20Model%20Overview.png)

## Excel Reports

### 1. [Profit and Loss (P&L) Report by Fiscal Year](https://github.com/RajanKumar-787/Finance_Analytics_Excel/blob/498cfb7e17d388eac7830c0eb920fb22db1f2c12/Reports/Profit%20and%20Loss%20(P%26L)%20Report%20by%20Fiscal%20Year.pdf)

This report analyzes key financial metrics such as net sales, cost of goods sold (COGS), gross margin, and gross margin % for AtliQ Hardware from FY 2019 to FY 2021.

![P&L Report by Fiscal Year](https://github.com/RajanKumar-787/Finance_Analytics_Excel/blob/356e63c4a615ce00b704114e2388e7d7a186d939/Images/Profit%20and%20Loss%20(P%26L)%20Report%20by%20Fiscal%20year.png)

### 2. [Profit and Loss (P&L) Report by Month](https://github.com/RajanKumar-787/Finance_Analytics_Excel/blob/498cfb7e17d388eac7830c0eb920fb22db1f2c12/Reports/Profit%20and%20Loss%20(P%26L)%20Report%20by%20Month.pdf)

This report analyzes the same key financial metrics on a quarterly and monthly basis for the FY 2019 to FY 2021.

![P&L Report by Month](https://github.com/RajanKumar-787/Finance_Analytics_Excel/blob/356e63c4a615ce00b704114e2388e7d7a186d939/Images/Profit%20and%20Loss%20(P%26L)%20Report%20by%20Month.png)

## Key Insights

- Net Sales grew sharply from $87.5M in 2019 to $598.9M in 2021 – a 584.6% increase, showing strong yearly growth.
- COGS increased from $51.2M in 2019 to $380.7M in 2021, meaning more products were produced and sold.
- Gross Margin increased from $36.2M to $218.2M, reflecting higher profitability.
- Gross Margin % fell from 41.4% to 36.4%, showing that rising production costs reduced overall profitability despite strong net sales growth.
- October, November, and December consistently recorded the highest sales across all fiscal years, due to festival seasons like Diwali and Black Friday.
- March 2020 recorded the lowest sales ($2.1M), reflecting the impact of the COVID-19 outbreak.

## Author & Contact

**Author:** Rajan Kumar  
**Email:** rajaninranchi787@gmail.com  
**GitHub:** [https://github.com/RajanKumar-787](https://github.com/RajanKumar-787)  
**LinkedIn:** [https://www.linkedin.com/in/rajankumar787/](https://www.linkedin.com/in/rajankumar787/)  

⭐ If you found this project helpful, please consider giving it a star!  
💬 Feedback and suggestions are always welcome!
