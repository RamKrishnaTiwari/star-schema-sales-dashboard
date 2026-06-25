# star-schema-sales-dashboard
An interactive sales dashboard built on a Star Schema data model, providing deep insights into total sales, product performance, state-wise metrics, and payment methods.
Star Schema Sales Dashboard

📌 Overview

This project features a comprehensive Sales Dashboard powered by an underlying Star Schema data model. It is designed to provide quick, high-level business insights while allowing stakeholders to drill down into specific product categories, regional performance, and salesperson contributions. The dashboard features a clean, purple-themed interface focused on total sales volume and product movement.

📊 Key Performance Indicators (KPIs)

The dashboard tracks the following high-level primary metrics at a glance at the top:

•	Total Sales: 4,457,869
•	Avg Sales: 8,105.22
•	Total Quantity: 7,245

📈 Visualizations & Insights

The dashboard includes several detailed visualizations to break down sales data from multiple perspectives:

•	Payment Method & Product Categories (Column Charts): Analyzes Total_Sales by Payment (showing relatively even distribution across Net Banking, Cash on Delivery, Credit Card, UPI, and Wallet) and Total_Sales by Product (highlighting Mobile, Books, and Furniture as top categories).

•	Sub Product Performance (Horizontal Bar Charts): 

o	Top 7 Sub Product by Sales: Identifies top sellers like T-Shirts, Color Sets, and TVs.
o	Bottom 7 Sub Product by Sales: Highlights underperforming items, including specific brands and sets like Xiomi, Apple, OnePlus, and Dough Set.

•	State-Wise Metrics (Pie Charts): Three pie charts break down performance geographically by Indian states (Uttar Pradesh, Gujarat, Madhya Pradesh, Tamil Nadu, and Maharashtra) across three metrics: Total Sales, Total Quantity, and Average Sales.

•	Sales by Manager (Donut Chart): Located at the bottom right, this chart breaks down the sales share by managing personnel, highlighting top contributors like Kuldeep Pandey (26.55%) and Harshit Patel (26.4%).

🎛️ Interactive Filters (Slicers)

A dedicated control panel on the right side of the dashboard provides dropdown slicers for targeted analysis:

•	Manager: Filter by specific sales managers.
•	State: Filter data by geographic regions.
•	Sub Product Name: Isolate performance for specific items.
•	Payment: Analyze specific transaction types.

🛠️ Tools Used

•	Data Modeling: Star Schema architecture (implied by the dashboard's title).
•	Business Intelligence Tool: (Note: Add your specific BI tool here, such as Power BI or Tableau, used for data visualization and interactive filtering).

🚀 How to Use

1.	Clone this repository: git clone https://github.com/your-username/star-schema-sales-dashboard.git
2.	Open the dashboard file (e.g., .pbix for Power BI) using your preferred Business Intelligence software.
3.	Use the dropdown slicers on the right-hand panel to interact with the visualizations and uncover specific insights for targeted states, managers, or products.
