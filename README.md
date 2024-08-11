# Python_Global-Superstore-Analysis

**Analysing Order Returns by Region**

Data Sources:
1.	Orders Table: Contains information about orders, including order IDs, regions, and other relevant details.
2.	Returns Table: Lists returned orders along with their order IDs and regions.
3.	People Table: Maps individuals to their respective regions.

Objectives:
•	Identify Return Rates: Calculate the return rates for each region based on the provided data.
•	Visualize Trends: Use visualizations to depict return rates across different regions.
•	Explore Correlations: Investigate any potential correlations between customer regions and return rates.

Steps:

1.	Data Preparation:
a.	Load the data from the three tables (CSV files, databases, etc.) into pandas DataFrames.
b.	Merge the tables using appropriate keys (e.g., region) to create a unified dataset for analysis.
2.	Data Cleaning:
a.	Handle missing values, if any, and ensure data consistency.
b.	Convert data types as needed (e.g., dates, numerical values).
c.	Calculating Return Rates:
d.	Count the total number of orders and returned orders for each region.
e.	Calculate the return rate as the percentage of returned orders out of total orders for each region.
3.	Visualizing Results:
a.	Utilize matplotlib or seaborn to create bar charts or pie charts illustrating return rates by region.
b.	Optionally, create geographical maps to visualize return rates geographically.
4.	Exploratory Analysis:
a.	Conduct exploratory analysis to identify any patterns or outliers.
b.	Explore correlations between customer regions (from the people table) and return rates.

Other Questions

1.	What are the regions with the highest and lowest return rates?

2.	Are there specific product categories or sub-categories associated with higher return rates?

3.	Is there a correlation between shipping mode and return rates?

4.	How do return rates vary over time?

5.	Are there any correlations between customer segments (e.g., consumer, corporate) and return behavior?

6.	Do specific cities or states within regions show higher return rates?

7.	What is the impact of discounts on return rates?

8.	How do return rates differ between new customers and repeat customers?

9.	Is there a relationship between shipping cost and return rates?
