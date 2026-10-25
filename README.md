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

### 2. 
---

## Book References

These are the key resources and books I used to guide my learning journey through EDA:

- *Practical Statistics for Data Scientists* by Peter Bruce and Andrew Bruce


---
## ⬅️⬅️ [Back to Main Profile](https://github.com/DhawaDG)
