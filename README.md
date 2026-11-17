# Global E-commerce Analytics
### End-to-End Business Intelligence & Data Analytics Project
**Analyzing global e-commerce sales, profitability, customer segments, product performance and shipping operations using Excel, MySQL, Tableau and Power BI.**

## 1. Project Overview

The Global E-commerce Analytics project is an end-to-end data analytics project designed to evaluate business performance using transactional e-commerce data.
The project focuses on transforming raw business data into meaningful insights through data cleaning, SQL analysis, KPI development, interactive dashboards and business reporting.
The analysis covers sales performance, profitability, product categories, customer segments, geographical markets, discounts, shipping and returns.

## 2. Business Problem

An e-commerce business generates large volumes of transactional data. However, raw data alone does not clearly explain business performance.
The key challenge is to identify:
- Which markets and product categories generate higher sales?
- Which categories and segments contribute to profitability?
- How do discounts relate to profit performance?
- How do shipping costs affect operational efficiency?
- What patterns can be identified in sales and order activity?
- How can management use dashboards to monitor business KPIs?

## 3. Project Objectives

1. Prepare and validate the e-commerce dataset.
2. Analyze sales, profit and order performance.
3. Identify market, category and segment performance patterns.
4. Evaluate discount and profitability relationships.
5. Analyze shipping and returns information.
6. Develop interactive dashboards using multiple BI tools.
7. Present business insights and recommendations.

## 4. Tools and Technologies

| Microsoft Excel - Data cleaning, PivotTables, PivotCharts, KPI reporting and dashboards |
| MySQL - Database creation, SQL queries, data validation and business analysis |
| Tableau - Interactive data visualization and dashboard development |
| Power BI - Power Query, data modeling, DAX measures and advanced visual analysis |

## 5. Dataset Overview

The project uses the Global Superstore dataset with three main data tables.
| Orders - Order, customer, product, sales, profit and shipping information |
| Returns - Returned order information |
| People - Regional manager information |

### Dataset Baseline

| Order-line records - 51,313 |
| Distinct orders - 25,035 |
| Total Sales - $12,643,332.95 |
| Total Profit - $1,467,402.45 |
| Total Quantity - 178,379 |
| Profit Margin - 11.61% |
| Returns records - 1,173 |
| People records - 13 |

**Profit Margin Formula:**

`Profit Margin = (Total Profit / Total Sales) × 100`

*Note: Order-line records and distinct orders are different measures. These figures are the project's baseline values and should be reconciled against the final dashboard outputs.*

## 6. Project Workflow

The project follows an end-to-end analytics workflow:

1. Data preparation and cleaning
2. Data validation and quality checks
3. Exploratory data analysis
4. SQL database development and querying
5. KPI calculation and business analysis
6. Dashboard development
7. Business interpretation and reporting

## 7. Excel Analysis

**Purpose:** Data preparation, exploratory analysis, KPI calculations and dashboard reporting.

### Activities

- Data cleaning and preparation
- PivotTable development
- PivotChart creation
- KPI development
- Sales and profit analysis
- Interactive dashboard reporting

### Excel Dashboard Preview

![Excel E-commerce Dashboard](<screenshots/excel e-commerce dashboard.png>)

## 8. MySQL Analysis

**Purpose:** Structured database management, data validation and business analysis.

### Activities

- Database creation
- Table management
- Data cleaning and validation
- SQL-based business analysis
- Aggregations and KPI calculations
- Sales, profit and order analysis

### SQL Topics

- SELECT, WHERE and ORDER BY
- GROUP BY and aggregate functions
- Joins
- Subqueries
- CASE statements
- Date-based analysis
- Business KPI calculations

**Project files:** [Explore MySQL Analysis](sql/)

## 9. Tableau Analysis

**Purpose:** Interactive business dashboards and visual exploration.

### Dashboard Analysis Areas

- Sales and profit trends
- Market performance
- Category and sub-category analysis
- Customer segment performance
- Geographical sales analysis

### Tableau Dashboard Preview

![Tableau E-commerce Dashboard](<screenshots/tableau e-commerce dashboard.png>)

**Project files:** [Explore Tableau Analysis](tableau/)

## 10. Power BI Analysis
**Purpose:** Data transformation, data modeling, DAX calculations and advanced business intelligence.

### Activities
- Data preparation using Power Query
- Data type correction
- Data model development
- Relationship management
- DAX measure creation
- KPI cards and interactive slicers
- Advanced business analysis visuals

### Key DAX Measures

**Total Sales**
```dax
Total Sales = SUM(Orders[Sales])
```

**Total Profit**
```dax
Total Profit = SUM(Orders[Profit])
```

**Profit Margin**
```dax
Profit Margin = DIVIDE([Total Profit], [Total Sales], 0)
```

**Total Orders**
```dax
Total Orders = DISTINCTCOUNT(Orders[Order ID])
```

**Total Quantity**
```dax
Total Quantity = SUM(Orders[Quantity])
```

### Power BI Dashboard Preview

![Power BI E-commerce Dashboard](<screenshots/power bi e-commerce dashboard.png>)
**Project files:** [Explore Power BI Analysis](powerbi/)

## 11. Key Performance Indicators

The project focuses on five primary business KPIs:
| Total Sales - Measures overall revenue performance |
| Total Profit - Measures business profitability |
| Profit Margin - Evaluates profit relative to sales |
| Total Orders - Measures distinct order volume |
| Total Quantity - Measures product quantity sold |

## 12. Business Analysis Areas

- Sales performance analysis
- Profitability analysis
- Market performance comparison
- Category and sub-category analysis
- Customer segment analysis
- Discount and profit relationship
- Shipping cost analysis
- Returns analysis

## 13. Business Recommendations

The following are areas for management investigation based on the analysis:
- Review low-profit and loss-making product categories.
- Evaluate discount policies against profitability.
- Monitor market-level sales and profit performance.
- Assess shipping costs and operational efficiency.
- Monitor customer segment contribution.
- Use KPI dashboards for regular business performance reviews.
*Recommendations should be refined using verified findings from the final analysis.*

## 14. Repository Structure

```text
global-ecommerce-analytics/
│
├── documentation/
│   ├── Project presentation
│   └── Project documentation
│
├── excel/
│   ├── Excel analysis workbook
│   └── README.md
│
├── sql/
│   ├── MySQL analysis scripts
│   └── README.md
│
├── tableau/
│   ├── Tableau workbook
│   └── README.md
│
├── powerbi/
│   ├── Power BI report
│   └── README.md
│
├── screenshots/
│   ├── excel e-commerce dashboard.png
│   ├── tableau e-commerce dashboard.png
│   ├── power bi e-commerce dashboard.png
│   └── README.md
│
└── README.md
```

## 15. Skills Demonstrated

- Data Cleaning and Data Validation
- Microsoft Excel and Dashboard Development
- MySQL and SQL Querying
- Exploratory Data Analysis
- Tableau Visualization
- Power Query
- Power BI Data Modeling
- DAX Measures
- KPI Development
- Business Intelligence
- Data Storytelling
- Analytical Problem Solving

## 16. Project Conclusion

This project demonstrates an end-to-end data analytics workflow using Excel, MySQL, Tableau and Power BI.
It combines data preparation, structured querying, business KPI development, interactive visualization and analytical reporting to support data-driven business decisions.
**Project Domain:** Global E-commerce Analytics
**Project Type:** Data Analytics | Business Intelligence
**Technologies:** Excel | MySQL | Tableau | Power BI
