# Interactive Coffee Sales Dashboard

## Introduction
This project follows a YouTube tutorial to create an interactive coffee sales dashboard using Excel. The dashboard visualizes key sales metrics, allowing for dynamic filtering through slicers and providing insights into coffee sales by time, product type, and customer demographics.

## Project Goal
The primary goal of this project is to transform raw coffee sales data into an interactive dashboard using data transformation techniques, PivotTables, and PivotCharts. The dashboard provides a comprehensive view of the business's sales trends and customer behavior.

## Skills and Tools
- **Data Transformation**: XLOOKUP, INDEX/MATCH, IF functions in Excel
- **Data Cleaning**: Handling missing data, formatting, removing duplicates
- **Data Analysis**: PivotTables for summarizing sales by time, product type, country, and customers
- **Data Visualization**: PivotCharts (Line charts, Bar charts)
- **Tools**: Microsoft Excel

## Data Gathering and Transformation
The raw data was organized into three tables: Orders, Customers, and Products. Data transformation involved:

- **Orders Table**: Includes order ID, date, customer ID, product ID, and quantity.
- **Customers Table**: Contains customer ID, name, email, country, and loyalty card status.
- **Products Table**: Provides product details such as coffee type, roast type, size, and unit price.

### Key Formulas:
- **XLOOKUP**: Used to pull customer data (name, email, country) from the Customers Table.
- **INDEX/MATCH**: Employed to retrieve product details (coffee type, roast type) from the Products Table.
- **IF Statements**: Cleaned and transformed data, handling missing values and replacing product and roast type abbreviations.
- **Sales Calculation**: `Sales = Unit Price * Quantity`.

## Data Cleaning
- Dates, sizes, and currency formatted for consistency.
- Duplicates removed, and the "Orders Table" was converted into an Excel Table for easier analysis.

## PivotTable and PivotChart Creation
Several PivotTables were created to aggregate sales data:

1. **Line Chart**: Shows total sales over time, broken down by coffee type (Arabica, Excelsa, Liberica, Robusta).
2. **Bar Chart (Sales by Country)**: Summarizes sales across different countries (U.S., Ireland, UK).
3. **Bar Chart (Top Five Customers)**: Displays the top five customers based on total sales.

### Slicers
Three slicers were added to filter the data:
- **Roast Type**: Dark, Light, Medium
- **Size**: 0.2kg, 0.5kg, 1kg, 2.5kg
- **Loyalty Card**: Yes/No

A **Timeline Slicer** was also added to allow filtering by date.

## Dashboard Assembly
All visuals, including charts and slicers, were combined to create an interactive dashboard. The layout was optimized to ensure the user can filter data seamlessly and gain insights on sales trends and customer preferences.

## Key Insights
- **Sales Trends**: Total sales over time show distinct peaks, with Arabica and Robusta leading in sales.
- **Geographical Performance**: The U.S. market accounted for the majority of sales, followed by the UK and Ireland.
- **Top Customers**: A few loyal customers contributed significantly to sales, indicating strong customer loyalty.

## Conclusion
This interactive dashboard enables the coffee shop to make data-driven decisions by providing an easy-to-use interface to analyze sales by coffee type, customer, and country. By utilizing Excel's data analysis and visualization features, we can quickly identify trends and optimize product offerings.

## Project Files
- `coffeeOrdersData.xlsx`: The original dataset.
- `coffeeOrdersProject.xlsx`: Contains the transformed data, PivotTables, and final dashboard.

## How to Use This Project
1. Download the Excel files.
2. Open the `coffeeOrdersProject.xlsx` to view and interact with the dashboard.
