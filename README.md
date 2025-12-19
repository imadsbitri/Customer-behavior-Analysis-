# Customer Shopping Behavior Analysis  
**End-to-End Data Analytics Project | Python • SQL • Power BI**

## Business Context
A retail company aims to better understand customer shopping behavior in order to improve **sales performance, customer engagement, and long-term loyalty**.  
Recent shifts in purchasing patterns across **demographics, product categories, and seasons** prompted the need for deeper analysis.

This project focuses on identifying how factors such as **discounts, customer reviews, purchase frequency, and subscription behavior** influence buying decisions and repeat purchases.

## Objective
Use consumer shopping data to:
- Identify trends and high-value customer segments
- Understand key drivers behind purchasing and loyalty
- Support data-driven marketing, pricing, and product strategies

## Dataset
- **3,900 customer transactions**
- **18 features**
- Covers customer demographics, purchase details, discounts, reviews, and shopping behavior
- **Data quality:** 37 missing values in the review rating column (handled during preprocessing)

## Data Preparation (Python)
- Cleaned and transformed raw data using **Pandas and NumPy**
- Standardized column names using **snake_case** for clarity and documentation
- Handled missing values by imputing review ratings with the **median per product category**
- Engineered new features to improve analysis:
  - `age_group`
  - `purchase_frequency_days`
- Performed consistency checks and removed redundant fields
- Loaded the final dataset into **PostgreSQL** for structured SQL analysis

## Data Analysis (SQL – PostgreSQL)
- Analyzed revenue distribution by gender and customer segment
- Identified repeat and high-value customers using purchase history
- Evaluated the impact of discounts on purchasing behavior
- Explored loyalty indicators such as previous purchases and review ratings

## Visualization (Power BI)
- Developed an **interactive Power BI dashboard** to communicate insights clearly
- Visualized:
  - Revenue and purchase trends
  - Customer segmentation patterns
  - Discount and seasonal effects on sales
  - Loyalty and repeat purchase behavior
 
![Power BI Dashboard](Screenshot%202025-12-19%20083006.png)

## Business Impact
- Provides actionable insights for **customer targeting and engagement**
- Supports optimization of **marketing and promotional strategies**
- Enables stakeholders to make **data-driven decisions** through clear visualizations

## Tools
- **Python:** Pandas, NumPy  
- **SQL:** PostgreSQL  
- **Business Intelligence:** Power BI  
