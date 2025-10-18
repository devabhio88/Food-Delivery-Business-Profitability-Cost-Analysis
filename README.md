# 🍴 Food Delivery Business Profitability & Cost Analysis using Python

## 📊 Overview
This project presents a **comprehensive financial analysis** of food delivery operations aimed at understanding the relationship between **cost, revenue, discount policies, and profit margins**.  
The goal is to identify opportunities to **reduce operational costs**, **optimize commission rates**, and **enhance profitability** through **data-driven decision-making**.

---

## 🧠 Objectives
- Evaluate the **financial performance** of a food delivery business.  
- Analyze the impact of **discounts, commissions, and delivery costs** on overall profitability.  
- Identify trends and correlations between **order value, commission rate, and profit margin**.  
- Derive **business insights** to improve revenue strategies and cost efficiency.

---

## 🧰 Technologies Used
| Category | Tools |
|-----------|--------|
| Programming | Python |
| Data Manipulation | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Date & Time Handling | datetime |
| Environment | Jupyter Notebook |

---

## 📂 Dataset Description
The dataset (`food_orders_new_delhi.csv`) contains detailed order-level records from a food delivery service, including:
- **Order Date and Time**
- **Delivery Date and Time**
- **Order Value**
- **Discounts and Offers**
- **Commission Fee**
- **Delivery Fee**
- **Profit**

> 🧾 *Note: The dataset used is simulated for educational purposes.*

---

## ⚙️ Data Processing Steps
1. **Data Loading & Cleaning**
   - Imported raw data using `pandas.read_csv()`.
   - Handled missing values and inconsistent entries.
   - Converted date-time columns using `pd.to_datetime()`.

2. **Discount Extraction & Calculation**
   - Parsed discount strings like `"20% off"` and `"₹50 off"` using a custom function.
   - Computed both **percentage-based** and **fixed amount** discounts.
   - Added `Discount Percentage` and `Discount Amount` columns.

3. **Profitability Metrics**
   - Derived `Commission Percentage`, `Effective Discount Percentage`, and `Profit Margin`.
   - Filtered **profitable orders** and analyzed their contribution to total revenue.

4. **Visualization**
   - Visualized cost, discount, and profit trends using **Matplotlib** and **Seaborn**.
   - Created charts for:
     - Profit Distribution
     - Commission vs. Order Value
     - Discount vs. Profit Margin
     - Delivery Cost Analysis

---

## 📈 Key Insights
- The **average commission percentage** for profitable orders was approximately **27.7%**.  
- The **average effective discount percentage** stood at around **5.6%**, suggesting discounts were moderate yet influential.  
- Orders with **optimized commission-to-discount ratios** yielded higher profitability.  
- Visual analysis revealed that **commission rates** and **discount policies** significantly impact profit margins.

---

## 📎 Project Structure

📁 Food-Delivery-Profitability-Analysis/
│
├── 📄 Food Delivery Business Profitability & Cost Analysis using Python.ipynb
├── 📊 food_orders_new_delhi.csv
├── 📘 README.md
└── 📈 results/ #(optional graphs, visual outputs)
