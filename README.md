# Customer Order Count Analysis

## Project Overview

This project focuses on analyzing customer ordering behavior using Microsoft Excel.

The objective is to calculate the total number of orders placed by each customer, identify the customers with the highest order frequency, and present the results through a structured analysis table and visualization.

This project was completed as part of the **VEDA Technology Level 1 – Day 20** task series.

---

## Objectives

- Calculate the number of orders placed by each customer.
- Organize customer-level order information in a structured table.
- Identify the top customers based on order count.
- Create a clear visual representation of the top customers.
- Apply professional Excel formatting for better readability and presentation.

---

## Dataset

The dataset contains customer and order-level information with the following fields:

| Column | Description |
|--------|-------------|
| Customer ID | Unique identifier assigned to each customer |
| Order ID | Unique identifier assigned to each order |
| Order Date | Date on which the order was placed |
| Product | Product associated with the order |
| Category | Product category |
| Sales | Sales amount generated from the order |

The dataset contains **30 orders across 6 customers**.

---

## Tools & Technologies

- Microsoft Excel
- Pivot Tables
- Excel Charts
- Data Sorting & Formatting
- Basic Data Analysis

---

## Analysis Performed

### 1. Customer Order Count

A PivotTable was created to calculate the total number of orders for each customer.

| Customer ID | Order Count |
|-------------|-------------:|
| C001 | 8 |
| C002 | 6 |
| C003 | 5 |
| C004 | 4 |
| C005 | 4 |
| C006 | 3 |
| **Grand Total** | **30** |

### 2. Top Customers

Customers were sorted according to their order frequency to identify the top three customers by order count.

| Customer ID | Order Count |
|-------------|-------------:|
| C001 | 8 |
| C002 | 6 |
| C003 | 5 |

### 3. Visualization

A column chart was created to visually compare the order counts of the top customers.

---

## Key Findings

- The dataset contains **30 total orders**.
- **C001** has the highest order count with **8 orders**.
- **C002** has placed **6 orders**.
- **C003** has placed **5 orders**.
- Customers **C004** and **C005** have placed **4 orders each**.
- **C006** has placed **3 orders**.

These results provide a simple view of customer ordering frequency and help identify customers with relatively higher engagement in the dataset.

---

## Project Structure

```text
veda-technology-task-20-customer-order-count_analysis/
│
├── VEDA_Technology_Task_20_Customer_Order_Count_Analysis.xlsx
└── README.md
