# Athletic Sales Analysis  
This project analyzes athletic sales data from 2020 and 2021 to determine various insights, such as the region with the most sales, the retailer with the most sales, and the day and week with the most women's athletic footwear sales.  


# Introduction
The goal of this project is to analyze sales data for athletic products to gain insights into sales performance across different regions, retailers, and time periods. The analysis includes combining data from multiple CSV files, cleaning the data, and performing various aggregations and transformations to answer specific business questions.  

# Data
The data used in this project consists of sales records for athletic products from 2020 and 2021. Each record includes information such as the retailer, invoice date, region, state, city, product, price per unit, units sold, total sales, operating profit, and sales method.  

# Setup
To run this analysis, you need to have Python and the following libraries installed:
pandas


## Combine and Clean the Data:  
- Import CSV files into DataFrames.  
- Display the DataFrames to understand their structure.  
- Check the data types of each DataFrame.  
- Combine the sales data from 2020 and 2021 into a single DataFrame.  
- Check for null values and ensure the data types are correct.  

## Determine which Region Sold the Most Products:  
- Use groupby and pivot_table to aggregate the total units sold by region, state, and city.  

## Determine which Region had the Most Sales:  
- Use groupby and pivot_table to aggregate the total sales by region, state, and city.  

## Determine which Retailer had the Most Sales:  
- Use groupby and pivot_table to aggregate the total sales by retailer, region, state, and city.  

## Determine which Retailer Sold the Most Women's Athletic Footwear:  
- Filter the data to include only women's athletic footwear sales.
- Use groupby and pivot_table to aggregate the total units sold by retailer, region, state, and city.  

## Determine the Day with the Most Women's Athletic Footwear Sales:  
- Create a pivot table with the invoice date as the index and total sales as the values.
- Resample the data into daily bins and sort by total sales.  

## Determine the Week with the Most Women's Athletic Footwear Sales:  
- Resample the data into weekly bins and sort by total sales.  

# Results  
The analysis provides insights into the following questions:  

- Which region sold the most products?
- Which region had the most sales?
- Which retailer had the most sales?
- Which retailer sold the most women's athletic footwear?
- What was the day with the most women's athletic footwear sales?
- What was the week with the most women's athletic footwear sales?

# Conclusion  
This project demonstrates how to analyze sales data using pandas to gain valuable business insights. By combining, cleaning, and aggregating the data, we can answer specific questions that help in understanding sales performance and making data-driven decisions.

