# 📊 AtliQ Hardware - End-to-End Power BI Dashboard Project

 This project was completed as part of the [Codebasics Data Analytics Bootcamp](https://www.codebasics.io/). In this case study, I designed and implemented a Business Intelligence dashboard for AtliQ Hardware — a fast-growing computer hardware company. The dashboard helps stakeholders monitor performance across Finance, Sales, Marketing, and Supply Chain functions.

##  Project Objective

AtliQ Hardware, which operates across multiple countries and sales channels, was struggling with slow and ineffective Excel-based reporting. The company suffered a major loss in Latin America due to a lack of actionable insights and real-time data access. Senior executives decided to adopt a data-driven culture and commissioned a data analytics solution using Power BI.

This project aims to:
- Build interactive dashboards for multiple business functions.
- Help executives make informed decisions.
- Monitor and improve sales, financials, and operational efficiency.

##  Problem Statement

> *How can AtliQ Hardware improve visibility into key performance metrics across its departments and markets to support growth and avoid data-driven losses?*

##  Tech Stack

- **Power BI**
- **SQL**
- **Microsoft Excel**
- **Power Query (M Language)**
- **DAX / DAX Studio**
- **PowerPoint**

##  Domain Knowledge Applied

- Data Analytics and Data Warehousing Concepts (OLTP vs. OLAP)
- Data Cataloging
- Star & Snowflake Schema
- Time Intelligence (YTD, YTG, Fiscal Year)
- Key Financial Metrics: Gross Sales, Net Sales, COGS, Gross Margin, Net Profit
- Forecasting Metrics: Net Error, Absolute Error, Forecast Accuracy

##  Key Business Metrics

| Metric | Description |
|--------|-------------|
| **Net Sales (NS)** | Actual revenue after pre and post-invoice deductions |
| **COGS** | Cost of goods sold including manufacturing and freight costs |
| **Gross Margin (GM)** | NS - COGS |
| **Net Profit (NP)** | GM - Other expenses |
| **Forecast Accuracy** | Measures the precision of forecasted sales |
| **Net/Absolute Error** | Error between forecasted and actual sales |

##  Data Overview

- **Customer Dimension**: 74 customers, 209 stores, 27 countries
- **Product Dimension**: 3 Divisions, 6 Segments, 14 Categories
- **Market Dimension**: 4 regions, 7 sub-zones, 27 markets
- **Fact Tables**: Monthly sales and forecast data

##  Data Modeling & Relationships

- Built Star Schema data model
- Created a Date Table using Power Query
- Defined many-to-one relationships between dimension and fact tables
- Used calculated columns and measures with DAX
- Used What-If parameters and dynamic slicers

##  Dashboard Views

| View | Description |
|------|-------------|
| **Finance View** | Profit & Loss statement to evaluate financial health |
| **Sales View** | Top/Bottom customers with key KPIs |
| **Marketing View** | Product performance and profitability |
| **Supply Chain View** | Forecast accuracy and demand planning |
| **Executive View** | High-level summary for decision-makers |

##  Workflow

1. **Project Planning & Scoping**  
   Created a Project Charter with timeline, stakeholders, success criteria.

2. **Data Collection & Cleaning**  
   Created a date table using Power Query (M Language), validated data.

3. **Transformation & Modeling**  
   Structured the data in a star schema, created relationships, DAX measures.

4. **Dashboard Design**  
   Interactive visuals, KPIs, bookmarks, tooltips, dynamic titles, and navigation buttons.

5. **Testing & Feedback**  
   Performed UAT (User Acceptance Testing), implemented stakeholder feedback.

6. **Deployment & Refresh**  
   Published to Power BI Service, scheduled auto-refresh with Gateway.

## 🔗 Interactive Dashboard

👉 [Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiY2ZhNGEzOWQtZTE3My00MWI2LWJhNmQtODc5Y2E3OGJlZjZlIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)


