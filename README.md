#  Vrinda Store Sales Analysis 📊

## 📝 Project Overview

This project presents a comprehensive analysis of the Vrinda Store's sales data. The goal is to uncover key insights into sales performance, customer behavior, and product trends to provide actionable recommendations for business growth, inventory optimization, and targeted marketing strategies.


---

## 🛠️ Tools & Technologies Used

| Tool | Purpose |
| :--- | :--- |
| **Microsoft Excel** | Data Cleaning, Data Processing, Pivot Tables, Data Analysis, and Visualization |

---

## 💡 Key Insights & Analysis

### 📈 Sales Analysis

#### **What is the total revenue generated?**
> **Insight:** The store generated a total revenue of **₹21,176,377**.
>
> _**Method:** Calculated by summing the `'Amount'` column._

#### **How many total orders were placed?**
> **Insight:** A total of **28,471** unique orders were placed.
>
> _**Method:** Performed a 'Distinct Count' on the `'Order ID'` column._

#### **What is the monthly trend of orders and revenue?**
> **Insight:** Sales peaked in **March** and then followed a general downward trend for the rest of the year.
>
> _**Method:** Extracted the month from the `'Order Date'` and used a pivot table to aggregate sales and orders by month._

#### **Which platform generated the most revenue?**
> **Insight:** **Amazon** is the top-performing channel, contributing **₹7.5M** in revenue.
>
> _**Method:** Grouped the data by `'Channel'` and summed the `'Amount'` for each._

#### **What is the Average Order Value (AOV)?**
> **Insight:** The Average Order Value (AOV) is **₹682.08**.
>
> _**Method:** Calculated by dividing Total Revenue by the Total Number of Unique Orders._

#### **How many orders were B2B vs non-B2B?**
> **Insight:** The business is overwhelmingly consumer-focused, with **99%** of orders being non-B2B.
>
> _**Method:** Segmented data using the `'B2B'` column._

---

### 📦 Product Analysis

#### **What are the top-selling categories and products?**
> **Insight:** The top categories are **"Set"** (12.4k units) and **"Kurta"** (10.5k units). The single best-selling product is SKU ``JNE3797-KR-L``.
>
> _**Method:** Grouped data by `'Category'` and `'SKU'` and summed the `'Quantity'`._

#### **What sizes are most frequently ordered?**
> **Insight:** The most popular sizes are **M**, **L**, and **XL**.
>
> _**Method:** Grouped data by `'Size'` and calculated the total quantity for each._

---

### 🧑‍💼 Customer Demographics

#### **Who are the primary customers?**
> **Insight:** The primary customer segment is **Women** (70% of customers) in the **"Adults"** age group.
>
> _**Method:** Used pivot tables to count distinct customers by `'Gender'` and `'Age Group'`._

#### **Which age group spends the most?**
> **Insight:** The **"Adults"** age group is the most valuable, contributing over **₹1.2 Crore** (57%) of the total revenue.
>
> _**Method:** Calculated the total `'Amount'` spent by each `'Age Group'`._

---

### 🗺️ Geographical Analysis

#### **Which states and cities are the top markets?**
> **Insight:** The top state for both orders and revenue is **Maharashtra**. The top city is **Bengaluru**.
>
> _**Method:** Grouped data by `'State'` and `'City'` to analyze order counts and revenue._

---

### 🚚 Order Fulfillment & Channel Performance

#### **What is the order fulfillment rate?**
> **Insight:** **92%** of all orders were successfully delivered, indicating a highly efficient fulfillment process.
>
> _**Method:** Grouped orders by `'Order Status'` and calculated the percentage for each status._

#### **Which channel is most preferred by different demographics?**
> **Insight:** **Amazon** is the dominant and most preferred channel across all genders and age groups, followed by Myntra and Flipkart.
>
> _**Method:** Created pivot tables to analyze the intersection of `'Channel'` with `'Gender'` and `'Age Group'`._

---

## 🎯 Final Recommendations

1.  **Focus on the Core Demographic:**
    *   Tailor marketing campaigns and product designs to **women** in the **"Adults"** age group, as they are the most valuable customer segment.

2.  **Optimize Inventory for Top Performers:**
    *   Prioritize stock for the **"Set"** and **"Kurta"** categories. Ensure popular sizes (**M, L, XL**) and hero products (like ``JNE3797-KR``) are always available, especially before peak months.

3.  **Strengthen Key Channels & Regions:**
    *   Double down on **Amazon, Myntra, and Flipkart**. Focus marketing spend and logistical efforts on top-performing states like **Maharashtra** and cities like **Bengaluru**.

4.  **Capitalize on Seasonality:**
    *   Launch major marketing campaigns and new collections in **January and February** to build momentum for the **March** sales peak.
