# Dynamic-Sales-Analysis-Report

**Overview:**


This Power BI report provides a comprehensive and interactive overview of sales performance, leveraging a star schema data model. The report is designed to offer flexible insights through a user-friendly interface by taking advantage of the power of bookmarks and buttons.
**Project Goals:** 

- Visualize key sales metrics: Total sales, revenue, profit margin, and customer acquisition cost.
- Track sales performance over time: Analyze historical data to identify trends and patterns.
- Compare sales performance across different regions and product categories.
- Identify top-performing sales representatives and underperforming areas.
- Enhance User Experience: The intuitive interface and interactive elements make the report easy to use and navigate


**Key Features:**


**Dynamic Filtering:** A powerful combination of buttons and bookmarks with slicers enables users to quickly filter data by customer, currency, or territory, providing a dynamic and engaging experience.
**Customizable Time Slicer:** A flexible time slicer allows users to drill down into specific time periods, such a month, quarter, or year.
**Comprehensive Sales Metrics:** The report visualizes key sales metrics, including:
**Dynamic Visual Title:** Expression-based titles that changes depending on the filter selection.
**Comprehensive Sales Metrics:** The report visualizes key sales metrics, including: 
- Total sales in the selected currency
- Total sales in the previous month
- Total sales over the entire period
- Sales comparison between the selected currency and other currencies
- Sales distribution across different territories (visualized on a map)
- Sales  comparison between the past month, quarter, and half-year
**Interactive Features:**
 - Slicers: Allow users to filter data based on specific criteria.
 - Drill-Down Functionality: Enable users to explore data at different levels of detail.
 - Bookmarks: Save specific report states for quick access.

**Data Model:** 

The report's data model is based on a star schema architecture, with the Sales table as the fact table and the following dimension tables:

DimCustomer
DimSalesTerritory
DimProduct
DimDate
DimCurrency
Tables: Provide detailed data breakdowns.
