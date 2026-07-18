# 📊 Madhav E-Commerce Sales Dashboard

An interactive Power BI dashboard tracking online sales performance, key KPIs, regional trends, customer performance, and category metrics across India for **Madhav Store**.

---

## 🖼️ Dashboard Preview

![Madhav Sales Dashboard](docs/dashboard.png)

---
<img width="628" height="350" alt="Image" src="https://github.com/user-attachments/assets/b2b563e1-6457-401c-ad66-8da0791b4a55" />

## 🎯 Project Objective

To assist the owner of Madhav Store in tracking and analyzing online sales across regions, payment modes, product categories, and customer segments to make data-driven business decisions.

---

## 🔑 Key Metrics & Insights

- **Total Sales Amount**: ₹118K
- **Total Profit**: ₹12K
- **Total Quantity Sold**: 1K units
- **Average Order Value (AOV)**: ₹33K
- **Top Product Category**: **Clothing** accounted for **66%** of total order quantity, followed by Electronics (21%) and Furniture (13%).
- **Preferred Payment Mode**: **Cash on Delivery (COD)** represented **44%** of sales, followed by UPI (22%) and Debit Card (10%).
- **Peak Profit Month**: **November** generated the highest profit (~₹10K), while December faced a dip.
- **Top Performing State**: **Maharashtra** generated the maximum sales revenue.
- **Top Sub-Categories**: Printers and Sarees generated the highest profits.

---

## 🛠️ Data Architecture & Relationships

The report uses two main tables connected via `Order ID`:

1. **`Orders` Table**: Contains order metadata (`Order ID`, `Order Date`, `CustomerName`, `State`, `City`).
2. **`Details` Table**: Contains transaction line details (`Order ID`, `Amount`, `Profit`, `Quantity`, `Category`, `Sub-Category`, `PaymentMode`).

---

## 🚀 How to Run This Project Locally

1. Clone or download this repository:
   ```bash
   git clone https://github.com/Shreya-88/Madhav-Ecommerce-Sales-Dashboard.git
