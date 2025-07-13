# Online Retail Sales-Dashboard - Power-BI

This project contains a Power BI dashboard created as part of a business case study to assist the CEO and CMO of an online retail store. The dashboard provides key insights derived from the Online Retail Dataset through careful data cleaning, transformation, and visualization.

## Objective
To generate business intelligence insights through a Power BI dashboard that answers specific questions requested by the CEO and CMO of a retail company. The analysis includes sales performance over time, top-performing countries, customer segmentation, and revenue trends.
- - - 

## Data Cleaning
Before visualization, the dataset was cleaned and transformed to ensure accuracy and reliability in insights:

1. Removed Negative Quantities: All rows with Quantity < 1 were filtered out.

2. Removed Invalid Prices: All rows with UnitPrice < 0 were removed.

3. Created Revenue Column: A new column was created using the formula:
Revenue = Quantity * UnitPrice
These transformations were done using Power BI's Power Query Editor.
- - - 

## File Structure

### Online-Retail-Sales-Dashboard
│                                                                                                                                                                                                                                             
├── Online_Retail_Sales_Dashboard.pbix     # Power BI dashboard file                                                                                                                                                                          
├── README.md                              # Project documentation                                                                                                                                                                            
└── sample_data/                           # (Optional) Folder with raw or sample cleaned dataset                                                                                                                                             
- - - 
## Dashboard Overview
The dashboard is organized into four separate tabs, each answering a specific business question:

### Tab 1 – Monthly Revenue (2011)
Question: What are the seasonal revenue trends in 2011?

1. Shows a time series line chart of monthly revenue in 2011.

2. Helps the CEO understand trends and forecast future revenue.

### Tab 2 – Top 10 Countries by Revenue (Excluding UK)
Question: Which 10 countries generate the highest revenue?

1. Bar chart displaying Top 10 Countries (excluding UK).

2. Revenue and Quantity Sold are shown using a clustered column and line combo chart.

3. Useful for the CMO to analyze global performance.

### Tab 3 – Top 10 Customers by Revenue
Question: Who are the top revenue-generating customers?

1. Bar chart sorted in descending order showing Top 10 Customers by Revenue.

2. Insightful for customer loyalty and personalized marketing strategies.
- - - 

## Tools Used
1. Power BI Desktop

2. Power Query Editor

3. DAX for calculated columns
- - - 
## How to View the Dashboard
1. Download and install Power BI Desktop.

2. Open the Online_Retail_Sales_Dashboard.pbix file.

3. Navigate between tabs to view each analysis.
- - - 
## Notes
Dataset used: Online Retail Dataset (or your source, if provided separately).

The dashboard is interactive – use filters and slicers to explore different dimensions.
- - - 

## How to Publish
To publish this dashboard:

1. Sign in to Power BI Desktop using your Microsoft account.

2. Go to File > Publish > My Workspace or your chosen workspace.

3. Share the dashboard link or embed it on a webpage.
- - -
