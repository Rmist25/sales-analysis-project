# TechnoEdge Sales Analysis

## Overview
The TechnoEdge sales dataset provides key insights into the company's sales performance, covering metrics such as Sales, Quantity, Discount, and Profit. By analyzing different categories, sub-categories, and products, trends and opportunities can be identified. Additionally, columns like Order Date, Dispatch Date, and Ship Mode offer insights into logistics and supply chain management. This project aims to use Power BI for data-driven decision-making.

## Project Tasks

### A. Data Cleaning
- Append sales data from 2020-2023 into a single table using the "Append Queries" feature.
- Merge the Profit column from the Profit table into the Sales table using the "Merge Queries" option.
- Change the data type of all columns in the Sales table using "Transform Data Types."
- Remove duplicates using the "Remove Duplicates" function.
- Filter out null values from the Sales table.
- Add an index column and rename it as "Sr. No."
- Use the Fill Down function to populate empty cells.
- Replace specific values with blank spaces.
- Extract Year, Month, Start of Month, Month Name, and Day from the Order Date column using the Date function.
- Create a conditional column to categorize sales as Low Profit or High Profit.

### B. Data View
- Display all geographical datasets (City, Country, State, Region) using Power BI’s map visual.

### C. Visual Insights
- Use Card visuals to show Total Sales, Net Profit, Total Customers, and Total Quantity (2020-2023).
- Display Total Sales trends from 2020-2023 using a Card visual.
- Use a Pie Chart to show the count ratio of total orders by category.
- Create a Stacked Bar Chart for the top-5 and bottom-5 selling products over the past year.
- Plot a Line Chart to visualize net profit trends, filtering by date hierarchy (Month, Quarter, Year).
- Display the top 10 customers by profit per country using a Table Visual.
- Show sales distribution by product categories using a Stacked Bar Chart.
- Visualize profit margins of all product categories using a Stacked Column Chart.
- Add labels to the Donut Chart to show the exact percentage of sales per segment.
- Filter the Stacked Bar Chart to show the profitability of the top 5 products.
- Use a Line and Stacked Column Chart to analyze the trends in sales and profit.
- Create a Scatter Chart to analyze the relationship between total sales and profit by segment.
- Add a Text Box to explain insights derived from the Scatter Chart.
- Display sales percentages by country using a custom Scroller visual.
- Enable tooltips in the Pie Chart for detailed sales breakdowns by sub-category.
- Add a "Start" button on the homepage linking to the Summary page.
- Include a "Summary Bookmark" button for direct project insights.

### D. Published Report
- Publish and share Power BI reports to enable collaboration and facilitate teamwork.

## How to Use
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/technoedge-powerbi.git
