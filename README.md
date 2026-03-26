# Strategic Procurement Analytics Dashboard

## Overview
This project presents a data-driven procurement analytics solution built using Power BI. The dashboard is designed to analyze organizational spending patterns, identify maverick spend (transactions with unapproved vendors), and evaluate supplier dependency risks. The objective is to support better procurement decisions through actionable insights.


## Problem Statement
Organizations often face challenges such as:
- Uncontrolled spending through unapproved vendors (maverick spend)
- Over-dependence on a limited number of suppliers
- Lack of visibility into category-wise expenditure

This project addresses these issues by transforming raw procurement data into meaningful insights.


## Key Features
- Total spend analysis across all transactions
- Category-wise expenditure breakdown
- Identification of maverick spend using approval logic
- Supplier-wise spend analysis to detect concentration risk
- Interactive dashboard for dynamic filtering and exploration


## Tools and Technologies
- Power BI (Data visualization and dashboard development)
- Power Query (Data cleaning and transformation)
- Excel / CSV (Data source)


## Data Processing
- Cleaned and transformed raw data using Power Query
- Standardized column names and data types
- Removed inconsistencies and duplicates
- Implemented business logic to classify approved and unapproved vendors


## Business Logic
- Maverick Spend: Transactions associated with unapproved vendors
- Supplier Risk: High dependency on specific suppliers based on total spend contribution

## Dashboard Components
- KPI Card: Total Spend
- Bar Chart: Spend by Category
- Pie Chart: Approved vs Maverick Spend
- Bar Chart: Supplier-wise Spend Distribution

## Insights Generated
- Identification of high-spend categories
- Detection of unapproved vendor transactions contributing to inefficiencies
- Recognition of supplier concentration risks
- Improved visibility into procurement patterns

## Repository Contents
- procurement_dashboard.pbix (Power BI project file)
- spend_analysis_dataset.csv (Dataset used)
- dashboard.png (Dashboard preview)

## Dashboard Preview
<img width="902" height="627" alt="image" src="https://github.com/user-attachments/assets/3592bbc2-86bc-4883-819e-c541f12a5f43" />

![Total Spend](![Total Spend](https://github.com/user-attachments/assets/aa654635-8e55-490b-87dd-bed199d0839a)
![Spend by Category](https://github.com/user-attachments/assets/4f63a276-4fc9-4f8e-b444-91a41548e534)
![Supplier Spend](https://github.com/user-attachments/assets/cdffce04-4179-4bcb-8b3e-ca81d2655bf7)
![Maverick Spend](https://github.com/user-attachments/assets/d6c94119-3e66-4d2a-8799-003350273ad2)


## Conclusion
This project demonstrates how procurement data can be leveraged to identify inefficiencies, reduce unnecessary costs, and improve supplier management through data analytics and visualization.


## Future Enhancements
- Integration with real-time procurement systems
- Advanced forecasting of procurement trends
- Supplier performance scoring models
- Automation using Python or SQL pipelines
