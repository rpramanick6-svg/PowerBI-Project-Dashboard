# PowerBI-Project-Dashboard
# Power BI Assignment Dashboard

## Overview
This project is a Power BI dashboard assignment focused on data modelling, desktop visualizations, interactive navigation, and DAX-based business calculations. The report appears to be designed as a multi-page dashboard with a landing page, navigation buttons, analytical visuals, and calculated metrics for business reporting. 

## What was built
The project covers multiple Power BI concepts across modelling, visuals, and DAX. Based on the exported presentation, the following components were created:

- A **data modelling** section, including tax slab calculation logic. 
- A **cardinality and desktop visualization** section using order quantity and sales fields. 
- A **scatter plot** built with sales and quantity, enhanced with a **play axis** on date to show changes over time. 
- A **landing page** with action buttons for navigation across report pages. 
- A **drilldown bar chart** using category and sub-category. 
- A **line chart** using sales, quantity, and order date.
- A **sales gauge chart** with a target value of 500000. 
- A DAX section with calculated columns, measures, grouped summaries, and trend analysis.

## DAX calculations included
The presentation notes show that this project includes several important DAX tasks for business analysis. These include:

- A **GST calculated column** applying an 18% tax slab on sales amount. 
- A **date difference column** to measure delay between order date and ship date. 
- **Sales bucket creation** based on defined conditions. 
- A **total sales measure** filtered for the Corporate segment. 
- A **gross profit margin measure** using gross profit divided by net sales. 
- A grouped table to identify **segment-wise average sales**. 
- A **cumulative sales** calculation for trend tracking. 
- A table visual showing **date, sales, and 3-day moving average**.
- A **year-over-year percentage sales change** metric. 

## Dashboard features
This project demonstrates several common Power BI reporting features used in business dashboards. It includes interactive page navigation, drilldown analysis, trend visualization over time, KPI-style gauge reporting, and analytical calculations through DAX.

## Skills demonstrated
This assignment shows hands-on work in the following areas: 

- Power BI Desktop report building
- Data modelling and relationships
- Visual design and interactivity
- Drilldown and play axis usage
- DAX calculated columns and measures
- Business KPI and trend analysis
- Dashboard navigation with action buttons

## Tools and concepts used
- Power BI Desktop 
- DAX 
- Data Modelling 
- Interactive Visualizations 
- KPI Reporting 

## Repository structure
```bash
powerbi-assignment/
├── README.md
├── assets/
│   ├── landing-page.png
│   ├── modelling-page.png
│   ├── visualization-page.png
│   └── dax-page.png
├── docs/
│   └── project-notes.md
├── export/
│   └── PowerBI-Assignment.pptx
└── project/
    └── PowerBI-Assignment.pbix
```

## Project purpose
The purpose of this assignment is to demonstrate the ability to build a structured Power BI report from raw business data, create useful visual analysis, and write DAX expressions for practical business questions such as taxation, delivery delay, profit margin, cumulative sales, moving averages, and year-over-year performance.

