---

## Exploratory Data Analysis (EDA) 


 This section highlights my proficiency in Exploratory Data Analysis (EDA), a critical step in any data science workflow. Through the use of Python libraries like Pandas and visualization tools, I demonstrate the ability to uncover patterns, detect anomalies, test hypotheses, and extract key insights from data. The projects listed here showcase a hands-on approach to preparing data for modeling and informing business decisions.

 
---
## Hands-on Projects

| SN | EDA Projects |
|:---:|:---|
| 1 | **[Nepal Population Analysis Tool](https://github.com/DhawaDG/Nepal_Population_Analysis_Tool)** |
| 3 | **[Exploratory Data Analysis (EDA) of a Real-World Dataset](https://github.com/DhawaDG/Exploratory-Data-Analysis-EDA-of-a-Real-World-Dataset)** |
| 3 | **[CLI EDA Analysis Tool](https://github.com/DhawaDG/CLI_ALL_EDA_ANALYSIS_TOOL)** |

---
## Topics Covered

- **Pandas:** loading, indexing, filtering, sorting (10h)
- **Handling missing values:** (8h)
- **Duplicates, renaming, reindexing:** (6h)
- **String operations, datetime operations:** (10h)
- **Data profiling:** (ydata-profiling) (8h)
- **Outlier detection:** IQR, Z-score (10h)
- **Descriptive statistics:** (8h)

---

## Handwritten Notes PDF

A collection of my detailed handwritten notes and summaries on these topics is available in PDF format.  

> **Note on Viewing PDFs on GitHub:**  
> If you encounter an "***Unable to render code block***" or preview error when opening a **📄 View PDF on GitHub** link, please reload the page or use the **⬇️ Download PDF** link right below it.

### 2. Building sql datasets for analytical reporting

### 1. EDA Using SQL

| Topics Covered | Page |
| :--- | :--- |
| Exploring the product table: product and product_category sample tables | `page 1` |
| Count of products per category (LEFT JOIN, GROUP BY, ORDER BY) | `page 1` |
| Output (category 4 has 0 products) | `page 2` |
| Exploring possible column values: vendor_inventory table | `page 3` |
| Preview the table (LIMIT 10) | `page 3` |
| Check for unique combinations (GROUP BY ... HAVING COUNT(*) > 1) | `page 3` |
| Analyze data ranges (MIN and MAX of market_date) | `page 4` |
| Analyze vendor activity (first and last market date per vendor) | `page 4` |
| Explanation of the vendor output (vendors 7, 8 and 4) | `page 5` |
| Exploring changes over time: vendor_inventory1 table | `page 6` |
| Vendor participation by year and month (EXTRACT, COUNT(DISTINCT vendor_id)) | `page 6` |
| Grouping process and counting distinct vendors | `page 7` |
| Output: vendors with inventory by month | `page 8` |
| Explore a specific vendor’s inventory (vendor_id = 7), with output | `page 8` |
| Identify seasonal vendors (COUNT(DISTINCT EXTRACT(MONTH ...)) as active_months) | `page 9` |
| Step-by-step walk-through (extract month per row, group, sort descending) | `page 9–10` |
| Detect market closures: months CTE (SELECT 1 UNION SELECT 2 ...) with LEFT JOIN | `page 11` |
| How UNION works, why the alias is only defined once | `page 11` |
| Whether SQL ties “month” to 30 days (it doesn’t) and the LEFT JOIN on EXTRACT(MONTH ...) | `page 12` |
| What happens in the LEFT JOIN (months with no data show NULL) and the output counts | `page 13` |
| Exploring inventory vs sales: vendor_inventory2 and customer_purchases tables | `page 14` |
| Query joining inventory to a sales subquery (LEFT JOIN on a SUM subquery) | `page 15` |
| Key differences: joining a table directly vs joining a subquery | `page 16` |
| COALESCE (replaces NULL with 0) | `page 17` |
| Joining subquery output | `page 17` |
| Final output (quantity available, sold, price, total sales) | `page 18` |

- [📄 View PDF on GitHub](https://github.com/DhawaDG/EDA_project_summary/blob/main/edausingsql.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/EDA_project_summary/raw/refs/heads/main/edausingsql.pdf)

### 2. Building sql datasets for analytical reporting.

| Topics Covered | Page |
| :--- | :--- |
| Business question to data question to data answer to business answer flow | `page 1` |
| Thinking through analytical dataset requirements (requirements, granularity, combining data, summarizing) | `page 1` |
| Error Code 1055: aggregated vs non-aggregated columns and GROUP BY | `page 2` |
| customer_purchases, market_date_info and vendor sample tables | `page 3` |
| Designing the reusable dataset: query joining the three tables with ROUND(SUM(...), 2) AS sales | `page 4` |
| Output of the reusable dataset (date, day, week, year, vendor, sales) | `page 4` |
| Using the dataset: total sales last week (subquery, BETWEEN) | `page 5` |
| Sales by vendor type | `page 6` |
| Sales on raining vs non-raining days | `page 7` |
| Custom analytical datasets in SQL (CTEs and views): customer_purchases1, market_date_info1, vendor1 tables | `page 8` |
| Using a CTE (sales_by_day_vendor) for weekly sales | `page 9` |
| CTE output (week 40, 70.50) | `page 10` |
| Views: definition and CTE vs view comparison (storage, reusability, performance, use case, syntax) | `page 10` |
| Create a view (vw_sales_by_day_vendor1) | `page 11` |
| Query the view (weekly sales) and output | `page 11–12` |
| Taking SQL reporting further: creating views, calculated fields, window functions, business questions | `page 13` |
| vendor_inventory2, customer_purchases2, vendor2 and product2 tables | `page 13` |
| Create a reusable view (vw_sales_per_date_vendor_product) with COALESCE, percent_of_available_sold, discount_amount | `page 14–15` |
| Subquery joining output (quantity sold and total sales) | `page 15` |
| Output of SELECT * from the view | `page 16` |
| Query the view, Example 1: percentage of sales per vendor per market date (SUM(...) OVER (PARTITION BY ...)) | `page 17` |
| PARTITION BY vs GROUP BY comparison | `page 17` |
| Role of OVER in window functions | `page 18` |
| Example 1 output (percent_of_vendor_sales) | `page 18` |
| Example 2: sales for a specific vendor and date range, with output | `page 19` |

- [📄 View PDF on GitHub](https://github.com/DhawaDG/EDA_project_summary/blob/main/buildingsqldatasetsforanalyticalreporting.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/EDA_project_summary/raw/refs/heads/main/buildingsqldatasetsforanalyticalreporting.pdf)
---

## Book References

These are the key resources and books I used to guide my learning journey through EDA:

- *Practical Statistics for Data Scientists* by Peter Bruce and Andrew Bruce


---
## ⬅️⬅️ [Back to Main Profile](https://github.com/DhawaDG)
