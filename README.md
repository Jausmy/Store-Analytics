# Data Portfolio: Store Sales & Transactions Dashboard

![Project-Main-Image](Assets/Images/Store%20Transaction%20Project%20Main%20Image.jpg)

## Overview
This report presents a comprehensive analysis of store sales and transaction data, focusing on identifying key revenue trends, understanding product category performance, and evaluating individual store performance. By examining sales patterns over time, across different product categories, and at the store level, we aim to provide actionable insights to optimize sales strategies, improve store operations, and drive overall business growth.

## Executive Summary
By examining key metrics such as total revenue, transaction count, average transaction value, and product category performance, we identified key trends and opportunities for improvement. A key insight from the analysis is that annual revenue experienced significant growth in 2021 compared to 2020, but slightly declined in 2022 [(see Revenue Summary Dashboard Values)](#Revenue-Summary-Dashboard). Based on the analysis, we recommend investigating the factors that contributed to the decline in 2022 and developing targeted strategies to revitalize sales growth. This could involve reviewing pricing strategies, enhancing marketing efforts, or optimizing product offerings to better align with customer demand. By implementing these recommendations, the company can potentially reverse the declining trend and achieve sustainable revenue growth [(see Potential Impact of Recommendations)](#Potential-Impact-of-Recommendations).

## Task/Objective
The objective of this analysis is to gain a comprehensive understanding of store sales and transaction patterns to identify key trends, evaluate performance, and provide data-driven insights for strategic decision-making. This involves:
-	Data Exploration: Exploring the raw data to understand its structure, identify key variables, and assess data quality.
-	Trend Analysis: Analyzing sales trends over time at different granularities (daily, weekly, monthly, quarterly, annually) to identify patterns, seasonality, and areas for potential improvement.
-	Comparative Analysis: Comparing sales performance across different product categories and individual stores to identify top performers, underperforming areas, and potential opportunities for optimization.
-	Performance Evaluation: Evaluating individual store performance based on key metrics such as total revenue, transaction count, and average transaction value to identify areas of strength and weakness.
-	Data Visualization: Creating interactive dashboards and visualizations to effectively communicate the key findings and insights from the analysis.

## Methodology
### Data Sources
The primary data sources for this analysis are two sales datasets:
-	Sales by date and product category: Contains information on total sales, distinct transaction count, total items sold, and transaction date for each product category.
-	Store transaction data: Contains information on store number, store name, state abbreviation, total items sold, total transactions, total revenue, and transaction date for each store.

![Data-Source-1](Assets/Images/Sales%20and%20Trans%20-%20Data%20Source%201.png)

![Data-Source-2](Assets/Images/Sales%20and%20Trans%20-%20Data%20Source%202.png)

### Tools Used
The following tools were used for data analysis and visualization:
-	Microsoft Excel – Data exploration
-	Tableau – Data visualization and analysis

### Data Exploration
Initial data exploration involved familiarizing ourselves with the dataset and identifying key variables. This included examining the distribution of sales across different product categories, time periods, and stores.

### Data Analysis Techniques
The following data analysis techniques were employed:
-	Trend Analysis: We analyzed sales trends over time at various granularities (daily, weekly, monthly, quarterly, annually) to identify patterns, seasonality, and areas for potential improvement. This involved aggregating sales data by different time periods and visualizing the trends to identify any significant fluctuations or consistent patterns in sales performance.
-	Comparative Analysis: We compared sales performance across different product categories and individual stores to identify top performers, underperforming areas, and potential opportunities for optimization. This involved grouping data by product category and store and calculating relevant metrics such as total revenue, transaction count, and average transaction value.
-	Performance Evaluation: We evaluated individual store performance based on key metrics such as total revenue, transaction count, and average transaction value to identify areas of strength and weakness. This involved comparing store performance against overall averages and identifying outliers or stores with significant deviations from the norm.
-	Diagnostic Analysis: This analysis was used to identify the root cause of the year-over-year decline in revenue observed in 2022. By examining various factors such as changes in consumer behavior, economic conditions, or competitor actions, we aimed to understand the underlying reasons for this decline.

## Future Considerations for Data Analysis
In the future, we can leverage additional data analysis techniques to further refine our understanding of sales patterns and optimize sales strategies. These techniques include:
-	Customer Segmentation: This technique can be used to group customers based on their purchasing behavior, demographics, or other relevant characteristics. By understanding the unique needs and preferences of different customer segments, we can tailor marketing campaigns, personalize product recommendations, and improve customer satisfaction.
-	Predictive Modeling: This technique can be used to forecast future sales, predict demand for specific products, and optimize inventory management. By building statistical models based on historical sales data and relevant factors, we can anticipate future trends and make proactive decisions to improve sales performance.
-	Geospatial Analysis: This method involves analyzing data with geographic components to understand the spatial distribution of sales and identify potential factors that influence store performance. By mapping sales data and overlaying data on factors such as population density, competitor locations, and demographic characteristics, we can identify areas with high or low sales performance and develop targeted strategies.

## Analysis of Sales and Transactions
### Revenue Summary Dashboard
The Revenue Summary Dashboard provides an overview of revenue trends at different time granularities:
-	Daily: Shows daily total revenue and day-over-day percentage change.

![Daily-Sales-Trends](Assets/Images/Sales%20and%20Trans%20-%20Daily%20Sales%20Trends.png)

-	Weekly: Shows weekly total revenue and week-over-week percentage change.

![Weekly-Sales-Trends](Assets/Images/Sales%20and%20Trans%20-%20Weekly%20Sales%20Trends.png)

-	Monthly: Shows monthly total revenue and month-over-month percentage change.

![Monthly-Sales-Trends](Assets/Images/Sales%20and%20Trans%20-%20Monthly%20Sales%20Trends.png)

-	Quarterly: Shows quarterly total revenue and quarter-over-quarter percentage change.

![Quarterly-Sales-Trends](Assets/Images/Sales%20and%20Trans%20-%20Quarterly%20Sales%20Trends.png)

-	Annually: Shows annual total revenue and year-over-year percentage change.

![Annual-Sales-Trends](Assets/Images/Sales%20and%20Trans%20-%20Annual%20Sales%20Trends.png)

#### Key Observations from Revenue Summary Dashboard
-	Daily revenue fluctuates: Daily revenue shows significant fluctuations, with some days experiencing double-digit percentage changes. This highlights the need to monitor daily sales patterns and identify potential factors that contribute to these fluctuations.
-	Weekly revenue shows some seasonality: Weekly revenue exhibits some seasonality, with higher revenue during certain weeks of the year. This suggests the potential for targeted promotions or marketing campaigns during peak seasons.
-	Monthly revenue fluctuates: Monthly revenue shows fluctuations from January to May, followed by six consecutive months of decline from June to November, and then an increase again in December. This pattern suggests a strong seasonal influence on sales performance.
-	Quarterly revenue shows consistent growth from 2020 to 2021: Quarterly revenue shows consistent growth throughout 2020-2021, indicating a positive overall trend.
-	Annual revenue shows significant growth in 2021: Annual revenue experienced significant growth in 2021 compared to 2020, but slightly declined in 2022. This highlights the need to investigate the factors that contributed to the decline in 2022 and develop strategies to revitalize sales growth.

### Product Revenue Summary Dashboard
The Product Revenue Summary Dashboard provides an overview of revenue trends by product category:
-	Total Annual Revenue by Product Category: Shows total annual revenue for each product category and year-over-year percentage change.

![Product-Category-YoY](Assets/Images/Sales%20and%20Trans%20-%20Total%20Rev%20By%20Cat%20%2B%20YoY.png)

-	Product Category Percentage of Total Annual Revenue: Shows the percentage contribution of each product category to total annual revenue.

![Product-Category-Percentage-Of-Total](Assets/Images/Sales%20and%20Trans%20-%20Total%20Rev%20By%20Cat%20%2B%20%25%20of%20Total.png)
  
-	Revenue Trend for Each Category: Shows the revenue trend for each category over time, with the year-over-year percentage change.

![Product-Category-Trends](Assets/Images/Sales%20and%20Trans%20-%20Product%20Category%20Rev%20Trends.png)

#### Key Observations from Product Revenue Summary Dashboard
-	Accessories dominate revenue: Accessories consistently generate the highest revenue among all product categories, accounting for 53% of total annual revenue each year.
-	Games show consistent performance: Games consistently contribute around 39% of total annual revenue.
-	Board games and collectibles have lower contributions: Board games and collectibles have relatively lower contributions to total revenue, with a consistent 6% and 2% respectively.
-	All categories experienced significant growth in 2021: All product categories experienced significant year-over-year revenue growth in 2021 compared to 2020.
-	Slight decline in revenue for most categories in 2022: Most product categories experienced a slight decline in revenue in 2022 compared to 2021.

### Store Performance Dashboard
The Store Performance Dashboard provides an overview of individual store performance:
-	Daily Revenue: Shows daily revenue for each store for the last 5 days and day-over-day percentage change.
-	Weekly Revenue: Shows weekly revenue for each store for the last 4 weeks and week-over-week percentage change.

![Store-Daily-&-Weekly](Assets/Images/Sales%20and%20Trans%20-%20Store%20Daily%20%2B%20Weekly.png)

-	Monthly Revenue: Shows monthly revenue for each store for the last 3 months and month-over-month percentage change.
-	Annual Revenue: Shows annual revenue for each store for the last 3 years and year-over-year percentage change.

![Store-Monthly-&-Annual](Assets/Images/Sales%20and%20Trans%20-%20Store%20Monthly%20%2B%20Annual.png)

-	Key Performance Indicators (KPIs): Shows average total revenue per store over the last 30 days, average number of transactions per store over the last 30 days, average items sold per store over the last 30 days, average revenue per transaction over the last 30 days, and average number of items per transaction over the last 30 days.

![Store-KPIs](Assets/Images/Sales%20and%20Trans%20-%20Store%20KPIs.png)

#### Key Observations from Store Performance Dashboard
-	Significant variation in store performance: There is significant variation in revenue and transaction count across different stores, highlighting the need for individualized performance evaluation and targeted improvement strategies.
-	Some stores consistently outperform others: Certain stores consistently generate higher revenue and transaction counts compared to others, suggesting potential best practices or operational differences that can be investigated.
-	KPIs provide a benchmark for comparison: The KPIs provide a benchmark for comparing individual store performance against overall averages.

### Sales Overview Dashboard
The Sales Overview Dashboard provides a comprehensive overview of key sales metrics:
-	Average Daily Revenue per Month: Shows average daily revenue per month with month-over-month percentage change.
-	Monthly Revenue: Shows monthly revenue with month-over-month percentage change.
![Sales-Overview-1](Assets/Images/Sales%20and%20Trans%20-%20Sales%20Overview%201.png)

-	Total Transactions by Month: Shows total transactions by month.
-	Total Units Sold by Month: Shows total units sold by month.

![Sales-Overview-2](Assets/Images/Sales%20and%20Trans%20-%20Sales%20Overview%202.png)

-	Average Revenue per Transaction: Shows average revenue per transaction with month-over-month percentage change.
-	Average Units per Transaction: Shows average units per transaction with month-over-month percentage change.

![Sales-Overview-3](Assets/Images/Sales%20and%20Trans%20-%20Sales%20Overview%203.png)

-	Average Revenue per Unit: Shows average revenue per unit.

![Sales-Overview-4](Assets/Images/Sales%20and%20Trans%20-%20Sales%20Overview%204.png)

#### Key Observations from Sales Overview Dashboard
-	Average daily revenue per month shows an upward trend: Average daily revenue generally shows an upward trend from 2020 to 2021, but stabilizes before declining in 2022.
-	Monthly revenue follows a seasonal pattern: Monthly revenue follows a similar seasonal pattern as observed in the Revenue Summary Dashboard, peaking in December every year except for 2022.
-	Transaction count and units sold follow similar trends: Total transactions and total units sold follow similar trends as monthly revenue, indicating a strong correlation between these metrics.
-	Average revenue per transaction remains relatively stable: Average revenue per transaction remains relatively stable over time staying between $125 and $130, with minor fluctuations.
-	Average units per transaction shows a consistent range: Average units per transaction remain consistent from 2020 to 2022, staying in a range of 2.42 units per transaction and 2.46 units per transaction.

## Recommendations
Based on the analysis of store sales and transaction data, the following recommendations are proposed:
-	Investigate 2022 Revenue Decline: Conduct a thorough investigation to understand the factors that contributed to the decline in annual revenue in 2022. This could involve analyzing market trends, competitor actions, customer feedback, and internal operational data.
-	Optimize Pricing and Promotions: Review pricing strategies and promotional campaigns to ensure they are aligned with market dynamics and customer preferences. This could involve conducting price elasticity analysis, A/B testing different promotions, or implementing dynamic pricing strategies.
-	Enhance Marketing Efforts: Enhance marketing efforts to increase brand awareness, attract new customers, and drive sales growth. This could involve targeted advertising campaigns, social media marketing, content marketing, or loyalty programs.
-	Optimize Product Offerings: Analyze product category performance and customer preferences to optimize product offerings. This could involve introducing new products, discontinuing underperforming items, or bundling products to increase average transaction value.
-	Improve Store Operations: Identify best practices from high-performing stores and implement them across all locations to improve operational efficiency and customer satisfaction. This could involve optimizing staffing levels, streamlining checkout processes, or enhancing store layouts.
-	Leverage Customer Segmentation: Implement customer segmentation strategies to tailor marketing efforts and product recommendations to specific customer groups. This could involve analyzing customer purchase history, demographics, and preferences to identify distinct customer segments and develop targeted strategies.

## Potential Impact of Recommendations
By implementing these recommendations, the company can anticipate the following positive outcomes:
-	Revitalized Sales Growth: By addressing the factors that contributed to the 2022 revenue decline and implementing targeted strategies, the company can potentially reverse the declining trend and achieve sustainable revenue growth.
-	Improved Profitability: Optimizing pricing, promotions, and product offerings can lead to increased profitability and improved financial performance.
-	Enhanced Customer Satisfaction: By focusing on customer needs and preferences, the company can enhance customer satisfaction and loyalty, leading to increased repeat business and positive word-of-mouth marketing.

## Limitations and Future Considerations
While this analysis provides valuable insights and recommendations, it's important to acknowledge certain limitations:
-	Limited Data: The analysis is limited to the available sales and transaction data. Access to more granular data, such as customer demographics, purchase history, and marketing campaign performance, would allow for a more comprehensive analysis and more personalized recommendations.
-	External Factors: External factors such as economic conditions, competitor actions, and changes in consumer behavior can significantly impact sales performance and should be considered in future analyses.

## Key Takeaways
This analysis provides valuable insights into store sales and transaction patterns. Here are the key takeaways:
-	Sales exhibit seasonality: Sales data shows clear seasonal patterns, with peaks in December.
-	Accessories are a key revenue driver: Accessories consistently generate the highest revenue among all product categories.
-	Store performance varies significantly: Individual store performance shows significant variation, highlighting the need for individualized evaluation and targeted improvement strategies.
-	2022 revenue decline warrants investigation: The decline in annual revenue in 2022 requires further investigation to identify the underlying causes and develop effective solutions.

By implementing the recommendations outlined in this report and continuously monitoring key performance indicators, the company can optimize its sales strategies, improve store operations, and achieve sustainable growth.
