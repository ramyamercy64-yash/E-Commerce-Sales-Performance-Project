# E-Commerce-Sales-Performance-Project
## 📌 Project Overview

This project presents an interactive **E-Commerce Sales Analysis Dashboard** developed in **Power BI**. It analyzes sales performance, customer behavior, product performance, and profitability to support data-driven business decisions.

The project demonstrates the complete data analytics workflow, including data cleaning, data modeling, DAX calculations, and dashboard development.

---

## 🎯 Business Problem

An e-commerce company wants to analyze its sales performance and customer behavior to answer key business questions such as:

- Which products generate the highest sales?
- Which customer segments contribute the most revenue?
- Which regions perform the best?
- How many orders are delivered, returned, or cancelled?
- What are the monthly sales trends?
- Which product categories generate the highest profit?

---

## 🛠️ Tools & Technologies

- Microsoft Excel
- Power Query
- Power BI
- DAX
- Git & GitHub

---

## 📂 Dataset

The project uses three related tables:

### Orders
- Order ID
- Order Date
- Customer ID
- Product ID
- Quantity
- Delivery Status

### Customers
- Customer ID
- Customer Name
- Gender
- Age Group
- Customer Segment
- City
- State
- Region

### Products
- Product ID
- Product Name
- Category
- Sub-Category
- Unit Price
- Sales
- Cost
- Profit

---

## 🧹 Data Cleaning

The dataset was cleaned using **Power Query** by:

- Removing duplicate records
- Handling missing values
- Standardizing text formatting
- Correcting data types
- Removing invalid records
- Creating calculated columns
- Preparing data for modeling

---

## ⭐ Data Model

The project follows a **Star Schema**.

```
Customers
     │
     │ Customer_ID
     ▼
Orders
     ▲
     │ Product_ID
Products
```

Relationships:

- Customers (1) → Orders (*)
- Products (1) → Orders (*)

---

## 📊 Dashboard Features

### KPI Cards
- Total Orders
- Total Customers
- Total Sales
- Total Profit
- Total Target
- Delivered Orders
- Returned Orders
- Cancelled Orders

### Sales Analysis
- Sales by Customer Segment
- Sales by Region
- Sales by Gender
- Sales by Age Group
- Sales by Category & Sub-Category
- Sales by City
- Sales by State

### Profit Analysis
- Profit by Customer Segment
- Profit by Category & Sub-Category

### Order Analysis
- Monthly Orders Trend
- Delivered Orders Trend
- Product-wise Order Distribution

### Geographic Analysis
- Sales by City (Map)
- Sales by State (Filled Map)

### Interactive Features
- Month Slicer
- Cross-filtering
- Interactive Visuals

---

## 📈 Dashboard Insights

- Generated **348K** in total sales.
- Achieved **90.22K** total profit.
- Processed **932** total orders.
- Served **250** unique customers.
- Delivered **426** orders successfully.
- Recorded **258** returned orders.
- Recorded **248** cancelled orders.
- Customer segments contribute differently to overall sales and profit.
- Sales performance varies across regions, states, and cities.

---

## 📁 Repository Structure

```
E-Commerce-Sales-Analysis/
│
├── Dataset/
│   ├── Orders.xlsx
│   ├── Customers.xlsx
│   └── Products.xlsx
│
├── PowerBI/
│   └── Ecommerce_Sales_Analysis.pbix
│
├── Images/
│   └── Dashboard.png
│
├── Documentation/
│   └── Project_Report.pdf
│
└── README.md
```

---

## 🚀 How to Run the Project

1. Clone this repository.
2. Open **Ecommerce_Sales_Analysis.pbix** using Power BI Desktop.
3. Refresh the data if required.
4. Explore the dashboard using the slicers and filters.

---

## 📸 Dashboard Preview

> Replace the image below with your dashboard screenshot.

(
Dashboard.png)
https://github.com/ramyamercy64-yash/Power-BI_Project/blob/main/Dashboard.png
---

## 💡 Future Enhancements

- Sales forecasting
- Customer retention analysis
- RFM analysis
- Executive summary page
- Drill-through reports
- Mobile-optimized dashboard

---

## 👩‍💻 Author

**Ramya**

**Aspiring Data Analyst**

### Skills
- Power BI
- Microsoft Excel
- Power Query
- DAX
- Data Cleaning
- Data Modeling
- Dashboard Development
- Business Intelligence

---
