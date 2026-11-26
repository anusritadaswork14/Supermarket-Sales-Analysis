# Supermarket Sales Analysis

A data analytics project developed as part of the Sapphire IQ Data Analytics Internship to explore supermarket sales performance, product categories, outlet characteristics, and statistical patterns.

## Project Overview

The project focuses on analyzing supermarket sales data to understand product performance, compare sales across different outlet types and locations, and examine the relationship between product visibility and sales.

The analysis aims to transform raw sales data into meaningful business insights that can support inventory planning and business decision-making.

## Project Objectives

1. **Overall Sales Performance:** Analyze total sales, average sales, product visibility, and key statistical measures.
2. **Product Category and Sales Comparison:** Identify the highest- and lowest-performing product categories, compare category contributions, and evaluate sales across outlet types.
3. **Outlet Performance and Sales Relationships:** Compare Low Fat and Regular product sales across outlets, examine product visibility against sales, and analyze category performance across outlet types.
4. **Statistical Analysis of Sales:** Evaluate average, median, minimum, maximum, standard deviation, variance, outliers, and average sales across different business segments.

## Tools and Technologies

- Python
- Pandas – Data manipulation and analysis
- NumPy – Numerical calculations
- Matplotlib – Data visualization
- Jupyter Notebook – Analysis and documentation

**Why these tools?**

Python libraries were used to clean, organize, summarize, and visualize the dataset. Pandas supported data manipulation and grouping, NumPy assisted with numerical analysis, and Matplotlib was used to create visual comparisons and statistical plots.

## Methodology

1. **Data Preparation:** Imported and inspected the dataset, identified missing values, handled missing item weights using median imputation, checked duplicate records, and standardized inconsistent product fat-content labels.
2. **Sales Analysis:** Calculated total sales, average sales, highest and lowest sales, and product visibility.
3. **Category and Outlet Comparison:** Used grouping and pivot tables to compare sales across product categories, outlet types, outlet sizes, and location tiers.
4. **Sales Relationship Analysis:** Compared Low Fat and Regular product sales and examined the relationship between item visibility and sales using correlation and a scatter plot with a trendline.
5. **Statistical Analysis:** Calculated median, standard deviation, variance, and used the Interquartile Range (IQR) method to identify potential sales outliers.

## Key Findings

- Total sales reached approximately **1,201,681.49** across 8,523 product records.
- Average sales per record were approximately **140.99**.
- Fruits and Vegetables recorded the highest total sales, while Seafood recorded the lowest.
- The top four product categories contributed approximately **50.6%** of total sales.
- Supermarket Type1 generated the highest total sales among outlet types.
- Tier 3 outlets recorded the highest total sales among location tiers.
- Low Fat products generated higher total sales than Regular products.
- Item visibility and sales showed virtually no linear correlation, with a correlation coefficient of **-0.0013**.
- The standard deviation of sales was approximately **62.28**. The IQR method identified no sales outliers.

## Conclusion

This project demonstrates how Python can be used to clean, analyze, and visualize supermarket sales data to identify meaningful business patterns.

The analysis highlights differences in product category performance, outlet contributions, and sales distribution. It also shows that item visibility alone had virtually no linear relationship with sales in the analyzed dataset.

Overall, the project strengthened practical skills in data cleaning, exploratory data analysis, statistical methods, Python programming, and communicating data-driven business insights.

## Project Details

- **Domain:** Retail and Business Analytics
- **Tools:** Python, Pandas, NumPy, Matplotlib
- **Environment:** Jupyter Notebook
- **Program:** Sapphire IQ Data Analytics Internship
