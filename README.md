# Zepto-Sales-Analysis

This project showcases a visually appealing and interactive **Excel Dashboard** for **Zepto Sales Analysis**. The dashboard is designed to help Zepto identify key business insights by analyzing important Key Performance Indicators (KPIs) such as **sales trends**, **product performance**, and **regional sales variations**. The dashboard allows the business to quickly identify strengths and weaknesses, providing actionable insights for improvement.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Data Cleaning & Formatting](#data-cleaning--formatting)
- [Dashboard Features](#dashboard-features)
- [Visualization and Insights](#visualization-and-insights)
- [How to Use](#how-to-use)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The **Zepto Sales Analysis Excel Dashboard** leverages **Excel's built-in features** to analyze sales data from Zepto, with the goal of presenting **meaningful insights** for improving business operations. 

The dashboard visually highlights KPIs and includes:

- **Total Sales**
- **Average Sales per Order**
- **Average Ratings**
- **Number of Grocery Items on Zepto**

Additionally, it provides an interactive view of sales data across different **locations**, **outlet types**, and **grocery products**.

### Key Features:
- **Sales Trends**: Visualize sales trends over time with interactive charts.
- **Product Performance**: Understand which products perform better based on various metrics like sales and ratings.
- **Regional Sales Analysis**: Examine how sales vary across different regions(tier1, tier2 and tier3 cities).
- **Interactive Slicers**: Filters that allow you to drill down into specific data based on location, outlet size, and grocery product.

## Dataset

The dataset used for this analysis is obtained from the following [Google Spreadsheet link](https://docs.google.com/spreadsheets/d/1g1UWMaqb3SZyqIKRNaobXS_yC-ag2JYN/edit?usp=sharing&ouid=107598287118156639512&rtpof=true&sd=true).

This dataset includes sales data from Zepto, such as:
- **Sales transactions**
- **Product details** (e.g., product name, type, fat content)
- **Regional sales data**
- **Outlet data** (e.g., outlet type, size)

## Data Cleaning & Formatting

Before building the dashboard, the raw dataset was cleaned and formatted. The following steps were performed:
1. **Data Cleaning**: Removed duplicates, handled missing values, and corrected inconsistencies in the data.
2. **Data Formatting**: Formatted data into usable structures for analysis, including grouping by product, location, and year.
3. **Calculation of KPIs**: Calculated key metrics like total sales, average sales per order, and average ratings.

## Dashboard Features

The dashboard includes several visual and interactive features to provide in-depth insights:

### 1. **Sales Key Metrics:**
   - **Total Sales**: Displays the total sales figure.
   - **Average Sales per Order**: Shows the average value of sales per order.
   - **Average Ratings**: Displays the average ratings of products.
   - **Number of Grocery Items**: Displays the total number of grocery products available on Zepto.

### 2. **Charts & Visualizations:**
   - **Sales by Location**: Column chart showing sales distribution across different regions.
   - **Yearwise Sales Trends**: Area chart depicting sales trends year-over-year.
   - **Sales by Outlet Type and Size**: Bar and Doughnut charts for analyzing sales performance based on outlet types and sizes.
   - **Sales Based on Fat Content of Items**: Chart showing sales variations based on the fat content of grocery products.

### 3. **Interactive Slicers:**
   - **Location Slicer**: Filter data based on different cities(Tier 1, Tier 2, and Tier 3).
   - **Outlet Size Slicer**: Filter data based on the outlet size.
   - **Grocery Product Slicer**: Filter data to view sales for specific grocery items by name.

You can single or multiple choices from one or more slicers to view sales accordingly.
These features enable the user to easily explore and analyze sales data in a dynamic and visually engaging way.

## Visualization and Insights

The dashboard generates several interactive charts to visualize key business insights:

- **Sales Trends**: The **yearwise sales trends** chart helps identify growth or decline patterns over the years.
- **Product Performance**: **Sales based on fat content** of items show which categories are performing better.
- **Regional Sales Variations**: **Sales by location** allow you to pinpoint regions that are driving the most sales and identify potential regions for growth.
- **Outlet Performance**: **Sales based on outlet type and size** help evaluate the performance of different outlets.

## How to Use

1. **Download the Excel File**: Download the provided Excel file containing the dashboard.
2. **Enable Macros (If Required)**: Ensure that macros and slicers are enabled in Excel for interactivity.
3. **Explore the Data**: Use the interactive slicers to filter the data by location, outlet size, or grocery products to see the corresponding visualizations.
4. **Analyze Key Metrics**: Check the summary of key metrics like **total sales**, **avg sales per order**, **avg ratings**, etc., and dive into visual trends for deeper insights.

## Dashboard Preview

![Screenshot 2024-12-10 174859](https://github.com/user-attachments/assets/ab59722f-2508-473e-b683-5fe917d655ea)


## Contributing

If you would like to contribute to this project, feel free to fork the repository, make changes, and submit a pull request. Contributions are welcome, and any improvements to the dashboard’s functionality, design, or insights are appreciated.

### Steps for Contribution:
1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature-branch`)
6. Create a pull request
