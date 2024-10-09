# Walmart-Sales-Exploration
An Exploration of external factors influencing Walmart Sales from 2010-2012

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Project Goals and Objectives](#project-goals-and-objectives)
- [Tools Used](#tools-used)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Data Analysis](#data-analysis)
- [Findings](#findings)
- [Recommendations](#recommendations)


## Project Overview

This project focused on exploring Walmart sales data from 2010-2012 to gain insight into how various factors such as air temperature, fuel price, inflation, and seasonal trends influence the company's sales performance. By analyzing these elements, the aim is to identify patterns that can help Walmart promote its sales strategies and improve performance during certain periods.

The findings from this analysis provide data-driven insights into how external factors influence consumer behavior, enabling Walmart to adapt and maintain a competitive edge in the retail market.

### Data Sources

The dataset used in this project was gotten from a public Walmart sales dataset on Kaggle. It includes a variety of variables such as:

1. Store.
2. Date.
3. Weekly sales amounts from Walmart stores.
4. Holiday Flag.
5. Temperature.
6. Fuel price.
7. Consumer Price Index (CPI).
8. Unemployment rates.

These variables provided the necessary information to explore how external environmental and economic factors influence Walmart’s sales.

### Project Goals and Objectives

The primary goal of this project was to understand how external factors affect Walmart's sales and provide data driven and actionable recommendations for improving sales performance. The specific objectives were:

1. Analyze Sales Trends by Temperature: This helps to investigate how different weather conditions influence consumer behavior and sales performance.
2. Examine the Effect of Fuel Price on Sales: This helps to understand how changing fuel prices influence consumer purchasing power.
3. Examine Sales Performance during Inflation Periods: This helps to identify the interaction between inflation rates and consumer spending at Walmart.
4. Explore Seasonal Trends and Monthly Sales: This helps to understand which months consistently drive the highest sales and which periods require marketing promotions.

### Tools Used

- Microsoft Excel: For data cleaning, creating pivot tables, and creating chart visualization of the data. [download here](https://microsoft.com)

### Data Analysis

The data analysis focused on several questions to understand Walmart's sales trends and performance:

1. Sales by Temperature: How do sales vary across different weather conditions?
2. Sales by Fuel Price: How do rising and falling fuel costs affect sales?
3. Sales by Inflation Rate: How do inflation rates impact consumer spending patterns at Walmart?
4. Sales Trends by Month: What are the best and worst-performing months for Walmart in terms of sales revenue?
5. Top Performing Stores: Which Walmart stores consistently generate the highest revenue, and what factors contribute to their success?

Pivot tables were used to visualize sales by various categories, enabling deeper insights into the relationships between these external factors and sales performance.

```Excel
=IFS(D2=0,"No Holiday",D2=1,"Holiday")
```
```Excel
=IFS(F190<50,"Cold Weather",F190<90,"Moderate Weather",F190>90,"Hot Weather")
```

### Findings

After exploration and analysis, I gained the folllowing insights;

- Moderate weather (50°F to 90°F) resulted in the highest sales. Cold weather had higher sales than hot weather, which may have been due to consumers stocking up during winter months.
  
- Sales were surprisingly higher when fuel prices were high. This could be due to periods of economic resilience or where consumers worry about stocking up on more essential goods due to the fear of further increase in price.

- The majority of sales occurred during low inflation periods, while high and very high inflation happened to have a decrease in sales which showcases that consumers have more purchasing power during periods of low inflation, which encourages higher spending.

- Highest amount of sales occurred in April, May, and July, while January, September, and November had the lowest sales which may mean that seasonality plays an important role in Walmart’s sales performance, with certain months likely benefiting from promotions or increased consumer spending.

- Out of all Walmart's 45 stores as at 2010-2012, store number 20 happened to be the highest-performing store , while the lowest-performing store among the top 5 is store number 2.


### Recommendations

Based on insights gained after exploration, I have the following recommendations;

- Walmart should focuson capitalizing on moderate weather conditions by offering promotions, launching new products, and creating special events to drive traffic during these periods.

- Walmart should focus on bundling products and offering discounts during high inflation to draw more cost-conscious consumers as promoting affordable product lines can help drive sales performance during tough economic periods.

- Walmart should ensure to target promotions and new product launches in months like January, September, and November which can help drive sales performamce throughout the year.

- Walmart could consider increasing inventory or testing new products in top-performing stores like Store 20, while focusing on improving customer experience in underperforming stores like Store 2.

Thank you for your time! 
