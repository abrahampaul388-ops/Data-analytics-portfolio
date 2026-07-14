# Walmart Sales Performance Analysis Dashboard

## Project Overview

This project analyzes Walmart's historical weekly sales data using Microsoft Excel. The objective was to transform raw sales data into an interactive dashboard that helps stakeholders understand sales performance across stores, departments, holidays, and key economic indicators.

The project demonstrates the complete data analysis process, including data preparation, data cleaning, data integration, analysis, visualization, and dashboard development.

---

## Business Problem

Walmart operates multiple stores with different departments and store types. Business leaders need a simple way to answer questions such as:

- Which stores generate the highest sales?
- Which departments perform best?
- Do holiday weeks affect sales?
- How do different store types compare?
- What trends exist over time?
- How do economic indicators relate to sales performance?

This dashboard was created to support data-driven decision-making by answering these questions visually.

---

## Dataset

The analysis is based on the Walmart Sales Forecasting dataset from Kaggle.

### Files Used

- train.csv
- stores.csv
- features.csv

The `test.csv` file was excluded because this project focuses on business analysis rather than predictive modeling.

---

## Tools and Skills

### Tools

- Microsoft Excel

### Skills Demonstrated

- Data Cleaning
- Data Integration
- XLOOKUP
- PivotTables
- Pivot Charts
- KPI Development
- Interactive Dashboard Design
- Data Visualization
- Business Analysis

---

## Data Preparation

The project combined data from multiple datasets into a single Master table.

The following steps were completed:

- Imported the datasets into Excel
- Merged Store information using XLOOKUP
- Merged economic indicators from the Features dataset
- Created additional analytical fields:
  - Year
  - Month Number
  - Month Name
  - Quarter
  - Week Number
  - Day Name
  - Sales Category
- Checked data consistency before analysis

---

## Dashboard Features

The dashboard includes:

- Total Sales KPI
- Average Weekly Sales KPI
- Number of Stores
- Number of Departments
- Monthly Sales Trend
- Sales by Store
- Sales by Department
- Sales by Store Type
- Holiday vs Non-Holiday Sales
- Interactive Slicers

---

## Key Insights

The analysis revealed several important business insights:

- Type A stores generated the highest sales among all store types.
- Sales varied significantly between stores, indicating differences in performance.
- Certain departments consistently produced stronger weekly sales than others.
- Holiday weeks influenced sales differently across departments.
- Monthly sales displayed seasonal trends that can support future planning.

---

## Business Recommendations

Based on the analysis:

- Focus inventory planning on high-performing departments.
- Study the operational practices of top-performing stores and apply successful strategies to lower-performing locations.
- Use seasonal sales patterns to improve staffing and promotional planning.
- Continue monitoring economic indicators when evaluating long-term sales performance.

---

## Dashboard Preview

![Dashboard](Dashboard.png)

---

## Project Structure

```
Walmart Sales Performance Analysis
│
├── Walmart_Sales_Performance_Analysis.xlsx
├── Dashboard.png
├── README.md
└── Dataset
    ├── train.csv
    ├── stores.csv
    └── features.csv
```

---

## Conclusion

This project demonstrates how Microsoft Excel can be used to transform raw business data into meaningful insights through data preparation, visualization, and interactive reporting. It showcases practical analytical skills that support business decision-making and performance monitoring.