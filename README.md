# 🛒 Blinkit Yearly Sales Data Analysis

---

## 1. Tools Used

- *SQL Server / MySQL*  
  To *query* and *process* the Blinkit sales data from the blinkit_data table.

- *Microsoft Excel*  
  To *present* the yearly sales data in an organized tabular format.

---

## 2. Elements Added

| Element | Purpose | Tool Used |
|--------|---------|-----------|
| **Year Column (Sale_Year)** | Extract year from date for grouping | SQL |
| *KPI: Total Yearly Sales* | Track overall revenue per year | SQL + Excel |
| *KPI: Average Sales per Order* | Understand customer order size per year | SQL + Excel |
| *KPI: Total Number of Orders* | Measure Blinkit platform activity | SQL + Excel |
| *KPI: Average Rating per Year* | Track product satisfaction yearly | SQL + Excel |
| *Sales by Item Fat Content per Year* | See customer preference for food types | SQL |
| *Top 5 Selling Item Types per Year* | Analyze best-selling products yearly | SQL |
| *Sales by Outlet Type per Year* | Understand store performance trends | SQL |
| *Sales Percentage by Outlet Size* | Discover contribution of small/medium/large stores | SQL |
| *Sales by Location Type* | Study regional performance | SQL |

---

## 3. Tables Created / Referenced

| Table Name | Description |
|------------|-------------|
| *blinkit_data* | Main sales data source |
| *Yearly_Sales_KPIs* (Query Output) | Table with Total Sales, Avg Sales, Orders, Ratings per Year |
| *Item_Fat_Content_Sales* (Query Output) | Sales by Fat Content per Year |
| *Top_Item_Types* (Query Output) | Top 5 Item Types by Sales for each Year |
| *Outlet_Sales_Breakdown* (Query Output) | Sales grouped by Outlet Type, Size, Location |

---

# ✅ Conclusion

By using *SQL* for querying and *Excel* for presentation, a clear and professional *Yearly Sales Analysis* of Blinkit was created.  
It covers all essential KPIs, yearly trends, and category-wise insights to support business decisions and sales monitoring.
