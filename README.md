# DecodeLabs Internship | Task 2: Exploratory Data Analysis (EDA)

## Project Overview

This project was completed as part of the **DecodeLabs Data Analytics Internship**.

The objective was to explore and analyze an e-commerce orders dataset using Microsoft Power BI, Power Query, and DAX to identify patterns in sales performance, order behavior, and order value distributions.

The analysis combines descriptive statistics, interactive data visualizations, and statistical outlier detection to provide a structured understanding of the dataset.

## Tools and Technologies

- **Microsoft Power BI Desktop:** Data visualization and report development
- **Power Query:** Data preparation and transformation
- **DAX:** Statistical calculations and analytical measures
- **Microsoft Excel:** Source dataset

## Dataset Overview

The dataset contains **1,200 e-commerce orders**, including information about:

- Order IDs and transaction dates
- Products, quantities, and prices
- Customer identifiers
- Order status and payment methods
- Referral sources and promotional coupons

## Analysis and Methodology

### 1. Descriptive Statistics

Calculated key metrics to understand the distribution of order values.

| Metric | Result |
|---|---:|
| Total Orders | 1,200 |
| Average Order Value | 1,053.97 |
| Median Order Value | 823.62 |
| Minimum Order Value | 11.39 |
| Maximum Order Value | 3,456.40 |

The average order value exceeds the median, consistent with a right-skewed distribution.

### 2. Product Performance Analysis

Created a horizontal bar chart to compare total sales values across product categories.

This analysis helps identify higher-performing products and compare their contribution to overall sales.

### 3. Sales Trend Analysis

Developed a time-series line chart to examine monthly sales fluctuations across the dataset's reporting period.

The visualization supports the identification of changes in sales activity over time.

### 4. Order and Payment Analysis

Analyzed order status distribution using a donut chart and compared payment methods using a column chart.

These visuals provide an overview of order outcomes and customer payment preferences.

### 5. Order Value Distribution

Grouped order values into bins to visualize transaction value frequencies.

The distribution is positively skewed, with more orders concentrated in lower value ranges.

### 6. Outlier Detection Using IQR

Applied the **Interquartile Range (IQR)** method to identify potentially unusual order values.

The outlier boundaries were calculated using:

- Lower limit = Q1 - 1.5 × IQR
- Upper limit = Q3 + 1.5 × IQR

**Results:**
- Potential outliers identified: **8**
- Percentage of total orders: **0.67%**

These values were flagged for further investigation rather than automatically removed.

## Power BI Report Pages

The interactive report contains five pages:

1. **Descriptive Statistics:** Key order value metrics
2. **Product Analysis:** Sales comparison by product
3. **Sales Trends:** Monthly sales performance
4. **Order Analysis:** Order statuses and payment methods
5. **Order Value Distribution:** Histogram, outlier count, detailed outlier records, and key findings

## Key Findings

- The dataset contains 1,200 orders.
- Order values are right-skewed, with an average value higher than the median.
- Product sales and monthly trends vary across categories and time periods.
- The IQR method identified eight potential high-value outliers.
- Potential outliers require further investigation before any corrective action is taken.

## Project Deliverables

| File | Description |
|---|---|
| `DecodeLabs_Project2_EDA.pbix` | Interactive five-page Power BI EDA report |
| `DecodeLabs Project2 EDA_Report.pdf` | Written exploratory analysis report |
| `Dataset for Data Analytics (1).xlsx` | Source dataset |
| `Image Oct 24, 2026, 07_52_30 PM.png` | Power BI report screenshot |
| `Image Oct 24, 2026, 07_52_45 PM.png` | Power BI report screenshot |

## How to Review the Project

1. Download `DecodeLabs_Project2_EDA.pbix`.
2. Open the file using **Microsoft Power BI Desktop**.
3. Navigate through the five report pages.
4. Review the descriptive statistics, sales visualizations, and outlier analysis.
5. Open the accompanying PDF for written documentation.

If Power BI requests a data source update, reconnect the source to the downloaded Excel dataset.

## Project Outcome

This project demonstrates practical skills in exploratory data analysis, statistical analysis, DAX measure creation, data visualization, and communicating business insights through Power BI.

## Internship Details

**Organization:** DecodeLabs  
**Track:** Data Analytics  
**Task:** 2 — Exploratory Data Analysis  
**Tools:** Power BI, Power Query, DAX, Microsoft Excel
