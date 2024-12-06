# Power BI Project: Dynamic Sales Analysis Report

**Overview:**


This Power BI report provides a comprehensive and interactive overview of sales performance, leveraging a star schema data model. The report is designed to offer flexible insights through a user-friendly interface by taking advantage of the power of bookmarks and buttons.

**Project Goals:** 

- Visualize key sales metrics: Total sales vs Total sales in particular currency.
- Track sales performance over time: Analyze historical data to identify trends and patterns.
- Compare sales performance across different regions.
- Enhance User Experience: The intuitive interface and interactive elements make the report easy to use and navigate.


**Key Features:**


**Dynamic Filtering:** A powerful combination of buttons and bookmarks with slicers enables users to quickly filter data by customer, currency, or territory, providing a dynamic and engaging experience.

**Dynamic Visual Titles:** Expression-based titles that changes depending on filter selection.

**Comprehensive Sales Metrics:** The report visualizes key sales metrics, including: 

- Total sales in the selected currency.
- Total sales in the previous month.
- Total sales over the entire period.
- Sales comparison between the selected currency and other currencies.
- Product sales distribution across different territories (visualized on a map).
- Sales comparison between the past month, quarter, and half-year.

  
**Interactive Features:**

 - Slicers: Allow users to filter data based on specific criteria.
 - Bookmarks : Save specific report states for quick access.

**Data Model:** 

The report's data model is based on a star schema architecture, with the Sales table as the fact table and the following dimension tables:

- DimCustomer
- DimSalesTerritory
- DimProduct
- DimDate
- DimCurrency
- 
Each dimension table is connected to the fact table through a **1-to-many** relationship (screenshot in the repository)

**technical Details:**

- **DAX Measures:**  Several DAX measures are created and grouped in a table(#Measures) to calculate key metrics, such as Last Quarter Sales, Last Semester Sales, Products Sales,...

- **Bookmarks:** Create dynamic and interactive reports that guide users through different insights by using 7 bookmarks that save specific states of your report, including filter selections, visual configurations, and page views( clear filter, Users ON/OFF, Currency ON/OFF, Territory ON/OFF).
  
- **Edit Interactions**  Customize how the visualizations on the report page filter and highlight each other. For example total sales last month and total sales amount cards do not interact with currency slicer.
  
- **Visualizations:**  The report includes various visualizations, including line and stacked column chart, card visuals, map chart and table.
  
- **Workspace:** create a content container that hold dashboards, reports, datasets, dataflows, and paginated reports, and provide a single location to work together on this project.

- **Publish the report:** upload the report to the created workspace(Sales).

**Sources:** Power BI course from 365 datascience.

**Demo:** 

Follow the demo video to know how to use the report well. demo video link :  https://www.youtube.com/watch?v=2CASUdTEgyQ

**Future Enhancements:**

- **Content update:** Consider adding additional visualizations or metrics based on specific business needs.
- **Update the data source:**  Replace getting data from local excel file with a connection to sql server.
- **Data Refresh:** Schedule data refreshes to keep the report up-to-date using a gateway.
- **Permissions:**  Control who can view and edit the report by creating roles and adjusting permissions in the workspace settings.
- **Sales Forecasting:** Accurate predictions of future sales trends
- **Unifie currency:** In this first version of the project,when we calculate the total sales amount we ignore the currency dimension which is wrong in real life, we should exchange sales into a unified currency so that the end-user could see the total sales in various currencies. 

