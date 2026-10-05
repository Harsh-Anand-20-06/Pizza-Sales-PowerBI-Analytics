# 🍕 Pizza Sales Analytics Dashboard

An interactive **Pizza Sales Analytics Dashboard** built using **Microsoft Power BI and SQL Server** to analyze sales performance, ordering trends, pizza category and size performance, and best/worst-selling products.

---

##  Dashboard Overview

### Sales Overview

![Pizza Sales Dashboard](https://github.com/user-attachments/assets/120d887d-649b-4600-989e-8a188cb1bc44)


The main dashboard provides an overview of:

- Total Revenue
- Average Order Value
- Total Pizzas Sold
- Total Orders
- Average Pizzas per Order
- Daily order trends
- Monthly order trends
- Revenue by pizza category
- Revenue by pizza size
- Total pizzas sold by category

---

##  Best & Worst Sellers

![Best Worst Sellers](https://github.com/user-attachments/assets/55b59a7f-3954-4c34-9767-6762721aafb5)

The second dashboard page analyzes the **Top 5 and Bottom 5 pizzas** based on:

- Revenue
- Quantity Sold
- Number of Orders

This helps identify the products contributing most and least to overall sales.

---

##  Date-Based Analysis

![Date Filtered Analysis](https://github.com/user-attachments/assets/e25674b0-9393-473d-9500-30d2a69afef4)

The dashboard supports interactive **date-range filtering**, allowing sales performance to be analyzed for a selected period.

The KPIs and visualizations dynamically update based on the selected date range.

---

##  Category Analysis

![Category Filtered Dashboard](https://github.com/user-attachments/assets/0f50ba23-ae3f-42c7-b550-163a1e3c5af6)

The dashboard also supports filtering by **Pizza Category**, allowing category-specific analysis of:

- Revenue
- Orders
- Pizzas Sold
- Average Order Value
- Average Pizzas per Order
- Daily and monthly trends

---

##  Date-Filtered Best/Worst Sellers

![Date Filtered Best Worst Sellers](https://github.com/user-attachments/assets/92d85ed4-2593-437f-a3b6-dfcd11937307)

Best and worst-selling pizzas can also be analyzed for a selected date range.

---

##  Category-Filtered Best/Worst Sellers

![Category Filtered Best Worst Sellers](https://github.com/user-attachments/assets/84cfe02d-60d4-4305-9b62-e5708e82db68)

Selecting a pizza category dynamically updates the best and worst-performing pizzas within that category.

---

#  Project Objective

The objective of this project is to analyze pizza sales data and build an interactive dashboard that answers key business questions such as:

- How much revenue was generated?
- How many pizzas were sold?
- How many orders were placed?
- What is the average order value?
- Which days generate the highest number of orders?
- Which months have the highest order volume?
- Which pizza categories contribute the most revenue?
- Which pizza sizes are most popular?
- Which pizzas are the best sellers?
- Which pizzas are the worst sellers?

---

#  Tools & Technologies

- **Power BI** – Dashboard development and visualization
- **SQL Server** – Data analysis and validation
- **SQL** – KPI calculations and analytical queries
- **DAX** – Power BI measures and calculations
- **Power Query** – Data preparation and transformation

---

#  Key KPIs

| KPI | Value |
|---|---:|
| Total Revenue | 817.86K |
| Average Order Value | 38.31 |
| Total Pizzas Sold | 49,574 |
| Total Orders | 21,350 |
| Average Pizzas per Order | 2.32 |

---

#  Analysis Performed

### 1. KPI Analysis

Calculated and visualized:

- Total Revenue
- Average Order Value
- Total Pizzas Sold
- Total Orders
- Average Pizzas per Order

### 2. Daily Trend Analysis

Analyzed total orders across the days of the week.

**Friday** has the highest order volume in the full-period dashboard.

### 3. Monthly Trend Analysis

Analyzed order volume across months to identify seasonal patterns.

**July** has the highest order volume in the full-year view.

### 4. Pizza Category Analysis

Analyzed revenue contribution across:

- Classic
- Supreme
- Chicken
- Veggie

The **Classic category** contributes the highest share of revenue.

### 5. Pizza Size Analysis

Analyzed revenue contribution across:

- Large
- Medium
- Regular
- X-Large
- XX-Large

**Large pizzas** contribute the highest share of revenue.

### 6. Best & Worst Sellers

Identified the Top 5 and Bottom 5 pizzas based on:

- Revenue
- Quantity Sold
- Total Orders

---

#  SQL Analysis & Validation

SQL Server was used to independently calculate and validate the metrics displayed in Power BI.

The SQL analysis includes:

- Total Revenue
- Average Order Value
- Total Pizzas Sold
- Total Orders
- Average Pizzas per Order
- Daily order trends
- Monthly order trends
- Revenue by pizza category
- Revenue by pizza size
- Pizzas sold by category
- Top 5 pizzas by revenue
- Bottom 5 pizzas by revenue
- Top 5 pizzas by quantity
- Bottom 5 pizzas by quantity
- Top 5 pizzas by total orders
- Bottom 5 pizzas by total orders

The SQL queries and corresponding SQL Server result screenshots are included in the repository.

---

#  Analysis Workflow

```text
Raw Sales Data
      ↓
SQL Server
      ↓
SQL Analysis & Validation
      ↓
Power BI Data Preparation
      ↓
DAX Measures
      ↓
Interactive Dashboard
      ↓
Business Insights
