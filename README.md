# Pizza Sales Analysis — Python Project

This project analyzes transactional pizza sales data using Python to uncover key business insights, trends, and KPIs for a pizza store.  
The goal is to help management make data-driven decisions around sales, marketing, operations, and inventory.

---

## 🔍 Project Overview

The Pizza Sales Analysis project is designed to:

- Analyze historical pizza sales transactions
- Identify revenue and demand patterns across categories, sizes, and products
- Understand customer purchasing behavior
- Provide actionable insights for operations, staffing, and promotions

The analysis is guided by a Business Requirements Document (BRD) and implemented end-to-end in a Jupyter Notebook.

---

## 🎯 Business Objectives

The main business objectives of this project are to:

- Calculate key KPIs:
  - **Total Revenue**
  - **Total Pizzas Sold**
  - **Total Number of Orders**
  - **Average Order Value (AOV)**
  - **Average Pizzas per Order**
- Understand sales distribution by:
  - Pizza **category** (e.g., Classic, Supreme, Veggie, Chicken)
  - Pizza **size** (S, M, L, XL, etc.)
  - Pizza **type/name**
- Analyze time-based sales trends:
  - Daily, weekly, and monthly trends
  - Hour-of-day sales patterns
- Identify:
  - **Top 5 best-selling pizzas**
  - **Bottom 5 least-selling pizzas**

These findings support pricing strategy, promotion planning, staffing, and inventory management. :contentReference[oaicite:1]{index=1}

---

## 📊 Dataset Description

**Primary dataset:** `pizza_sales.csv`  

Key fields include: :contentReference[oaicite:2]{index=2}

- `order_id` → Unique identifier for each order  
- `pizza_id` → Unique identifier for each pizza  
- `pizza_name` → Name of the pizza sold  
- `quantity` → Number of pizzas in each line item  
- `total_price` → Total revenue for that line (quantity × unit price)  
- `date`, `time` → Order date and time for time-based analysis  
- `pizza_category` → Category of the pizza (Classic, Supreme, Veggie, Chicken, etc.)  
- `pizza_size` → Size of the pizza (S, M, L, XL, etc.)  

Additional Excel versions of the dataset may be used for exploration and quick checks.

---

## 📌 Key Performance Indicators (KPIs)

The analysis computes the following KPIs: :contentReference[oaicite:3]{index=3}

- **Total Revenue** = Σ `total_price`  
- **Total Pizzas Sold** = Σ `quantity`  
- **Total Orders** = Count of unique `order_id`  
- **Average Order Value (AOV)** = Total Revenue ÷ Total Orders  
- **Average Pizzas per Order** = Total Pizzas Sold ÷ Total Orders  

These metrics provide a high-level view of business performance.

---

## 📈 Analysis & Visualizations

The notebook includes Python-based analysis and visualizations to answer:

- **Daily Trend:**  
  Sales by day of the week to support staffing decisions and operations planning.
- **Hourly Trend:**  
  Sales by hour of the day to identify peak times and rush hours.
- **Monthly Trend:**  
  Revenue and order volume by month to understand seasonality and promotional impact.
- **Sales by Category:**  
  % of revenue and quantity by pizza category (e.g., Classic, Veggie) to understand customer preferences.
- **Sales by Size:**  
  Performance of different pizza sizes (S/M/L/XL) to inform pricing and inventory.
- **Total Pizzas Sold by Category:**  
  Helps with ingredient planning and menu strategy.
- **Top 5 Best-Selling Pizzas:**  
  Used to highlight star products and potential candidates for promotions.
- **Bottom 5 Least-Selling Pizzas:**  
  Helps identify items that may need improvement, repositioning, or removal from the menu. 

---

## ❓ Business Questions Answered

This project helps answer: 

- What is the **total revenue** generated?  
- How many **pizzas** were sold in total?  
- How many **orders** were placed?  
- Which **categories** and **sizes** perform best?  
- Which pizzas are the **top** and **bottom** performers?  
- What is the **Average Order Value** (AOV)?  
- What is the **Average Pizzas per Order**?  
- What are the **sales trends** by day, month, and time of day?

---

## 🧰 Tools & Technologies

- **Python**
  - pandas — data cleaning & transformation  
  - matplotlib / seaborn — visualizations  
- **Jupyter Notebook** — end-to-end analysis and reporting  
- **CSV / Excel** — raw data storage and inspection  
- **Business Requirements Document (BRD)** — project scoping and alignment  

---

## 📁 Files in This Project

Typical files included in this repository:

- `pizza_sales_analysis.ipynb` — Main Jupyter Notebook with full analysis  
- `pizza_sales.csv` — Core dataset  
- `pizza_sales.xlsx` — Optional Excel version of the dataset  
- `Pizza_Sales_BRD.docx` or `Pizza_Sales_BRD.pdf` — Business Requirements Document  

(Use your actual filenames in the repo as needed.)

---

## 🧠 Key Takeaways

From this project, I practiced:

- Translating a **BRD** into a real data analysis workflow  
- Writing **Python code** to calculate KPIs and trends  
- Using **visualizations** to communicate insights clearly  
- Connecting business questions to data-driven answers  
- Framing **actionable recommendations** for management based on data :contentReference[oaicite:6]{index=6}  

---

## 🔗 Connect With Me

- **Portfolio:** https://hashimgilani.github.io  
- **LinkedIn:** https://linkedin.com/in/syedhashimgilani  
- **Email:** hashimgilani331@gmail.com  

⭐ *Thanks for checking out this project!*
