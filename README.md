# Amazon Sales Data Analysis

This project focuses on cleaning, preprocessing, and analyzing Amazon sales data. The analysis includes visualizations of sales trends, revenue, and profit over different periods and regions.

## Data Cleaning and Preprocessing

1. **Handle Missing Values**: Checked and removed any missing values.
2. **Check for Duplicates**: Identified and removed duplicate rows.
3. **Data Type Conversion**: Converted date columns to datetime format and ensured numerical columns are of numeric type.
4. **Extract Year and Month**: Extracted the year and month from the order date for further analysis.

## Data Analysis and Visualization

The project provides the following analyses:
- **Sales per Month**: Monthly sales trends for each year.
- **Sales per Year**: Total units sold per year.
- **Total Revenue per Year**: Total revenue generated per year.
- **Total Profit per Year**: Total profit earned per year.
- **Sales by Region**: Total units sold in each region.

## Usage

1. **Install Dependencies**: Ensure you have Python and the required libraries installed.
   ```bash
   pip install pandas matplotlib seaborn
