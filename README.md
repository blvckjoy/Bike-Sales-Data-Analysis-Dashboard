# Bike Sales Dashboard Project

## Overview
This project is a comprehensive analysis of bike sales data, visualized through an interactive dashboard. The dashboard provides insights into customer demographics, purchasing behavior, and regional sales trends based on a dataset of 1,000 customers. It includes various charts and pivot tables to help understand factors influencing bike purchases.

## Data Source
The data is sourced from an Excel file named `Bike_Sales_Data_Analysis.xlsx`, containing multiple sheets:
- **bike_buyers**: Raw data with 1,013 rows of customer information including ID, Marital Status, Gender, Income, Children, Education, Occupation, Home Owner, Cars, Commute Distance, Region, Age, and Purchased Bike.
- **Working Sheet**: Processed data with an additional `Age Brackets` column categorizing ages into Adolescent, Middle Age, and Old.
- **Pivot Tables**: Summarized data with counts and averages, such as Purchased Bike counts by Commute Distance, Age Brackets, Regions, and Education, as well as Average Income by Gender and Purchased Bike status.
- **Dashboard**: A textual representation of the dashboard layout.

## Features
- **Average Income Per Purchase**: Bar chart comparing average income by gender and purchase status.
- **Customer Age Brackets**: Line chart showing the distribution of purchases across Adolescent, Middle Age, and Old age groups.
- **Sales By Region**: Pie chart illustrating sales distribution across Europe, North America, and Pacific regions.
- **Customer Commute**: Line chart depicting purchase trends based on commute distance.
- **Sales By Education**: Bar chart showing purchase counts by education level and purchase status.

## Installation
1. Ensure you have a compatible spreadsheet software (e.g., Microsoft Excel, Google Sheets) to view and manipulate the data.
2. Download the `Bike_Sales_Data_Analysis.xlsx` file.
3. Open the file to explore the raw data, processed data, pivot tables, and dashboard layout.

## Usage
- Navigate to the `Dashboard` sheet to view the visual representation of the data.
- Use the `Pivot Tables` sheet to analyze summarized data and derive insights.
- Modify the `Working Sheet` to add new calculated fields or adjust age brackets as needed.
- The `bike_buyers` sheet can be used for raw data analysis or further processing.

## Insights
- **Gender and Income**: Males tend to have a slightly higher average income ($58,062) compared to females ($54,580), with a notable difference in purchase behavior.
- **Commute Distance**: Customers with a 0-1 mile commute have the highest purchase count (366), while longer commutes (above 10 miles) show the lowest (111).
- **Age Brackets**: Middle Age customers (676 total) dominate both purchase and non-purchase categories, with 375 purchases.
- **Region**: North America has the highest customer base (508), but Pacific shows a higher purchase rate relative to its population.
- **Education**: Bachelors and Graduate Degree holders show higher purchase counts, indicating a correlation with education level.

## Contributing
Contributions are welcome! Please fork the repository, make your changes, and submit a pull request. Ensure to update the documentation and tests accordingly.
