
## Key Insights
- Identified top-performing regions by revenue and profit
- Highlighted best-selling and underperforming products
- Analyzed customer contribution to total sales
- Revealed seasonal trends affecting sales performance

## Example SQL Query
```sql
SELECT region, SUM(sales) AS total_sales
FROM sales
GROUP BY region
ORDER BY total_sales DESC;
