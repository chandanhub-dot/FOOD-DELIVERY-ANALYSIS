# 🍔 Food Delivery Analytics: Revenue Drivers Dashboard

A dynamic, interactive **Microsoft Excel dashboard** designed to analyze revenue performance across cities, categories, and customer behavior in a food delivery platform—focusing on identifying key growth drivers and actionable business insights.

---

## 🟦 1. Short Description / Purpose

This dashboard provides a comprehensive analysis of food delivery data to uncover key revenue drivers across geography, product categories, and customer behavior. It enables stakeholders to explore trends, identify opportunities, and support data-driven decision-making.

---

## 🟦 2. Tech Stack

The dashboard was built using:

- 📊 **Microsoft Excel** – Dashboard development  
- 📂 **Pivot Tables** – Data aggregation & KPI calculations  
- 🎛️ **Slicers** – Interactive filtering  
- 📈 **Charts** – Bar, Line, and Donut visualizations  
- 🧠 **Data Transformation** – Feature engineering (Month, Day, Food Type)  
- 📁 **File Format** – `.xlsx` (dashboard), `.png` (preview)

---

## 🟦 3. Data Source

**Source:** Swiggy Dataset  
👉 https://drive.google.com/drive/folders/1YCMSykZ-rv27HYPlADonBKDGAgTfsjsa

The dataset includes:

- City & State  
- Order Date  
- Restaurant Name & Category  
- Dish Name  
- Price (INR)  
- Rating & Rating Count  

Each row represents a customer order, enabling detailed analysis of revenue trends and demand patterns.

---

## 🟦 4. Data Preparation

- Cleaned and structured raw data  
- Created derived columns (**Month**, **Day**)  
- Engineered **Food Type (Veg / Non-Veg)** using keyword-based classification  
- Standardized categorical fields  
- Prepared analytical layer using Pivot Tables  

---

## 🟦 5. Features / Highlights

### 🔹 Business Problem

The food delivery platform lacks clear visibility into **what drives revenue growth** across cities, categories, and customer segments.

**Key business questions include:**

- **Which cities contribute the highest revenue and where should expansion be prioritized?**  
- **Which categories and dishes drive the majority of orders and revenue?**  
- **What are customer ordering patterns across weekdays vs weekends?**  
- **How does Veg vs Non-Veg demand vary across markets?**  
- Which restaurants are top performers and how concentrated is revenue among them?  
- Are there underperforming categories or cities with growth potential?  
- **Is revenue growth driven by order volume or higher Average Order Value (AOV)?**  
- How consistent is revenue across months and are there seasonal trends?  
- What role do customer ratings play in influencing demand?  
- Where should marketing, promotions, or partnerships be focused to maximize ROI?  

---

### 🔹 Goal of the Dashboard

To build an **interactive analytical tool** that:

- Identifies key revenue drivers  
- Enables dynamic exploration using filters  
- Supports strategic decisions in marketing, expansion, and operations  

---

### 🔹 Walkthrough of Key Visuals

#### 📊 KPI Cards (Top Section)
- **Total Revenue:** ₹5.3M+ – Overall platform performance  
- **Total Orders:** 197K+ – Order volume indicator  
- **Average Order Value (AOV):** ₹88 – Customer spending behavior  
- **Top City:** Bengaluru – Highest revenue contributor  

---

#### 🌍 Filter Panel (Slicers)
Interactive filters for:
- City  
- Restaurant  
- Category  
- Month  

👉 Enables dynamic analysis across different segments and time periods.

---

#### 🏙️ Top 5 Cities by Revenue (Bar Chart)
Ranks cities based on revenue contribution.

👉 Identifies **high-performing markets** and supports **expansion strategy decisions**.

---

#### 📈 Monthly Revenue Trend (Line Chart)
Displays revenue trends across months.

👉 Helps identify **growth consistency**, **seasonality**, and performance fluctuations.

---

#### 🍽️ Revenue by Category (Bar Chart)
Breakdown of revenue across food categories.

👉 Highlights **top-performing categories** and **demand concentration**.

---

#### 📅 Daily Trend (Column Chart)
Shows order distribution across weekdays.

👉 Reveals **peak demand days (weekends)** and **customer behavior patterns**.

---

#### 🥗 Revenue by Food Type (Donut Chart)
Compares **Veg vs Non-Veg revenue share**.

👉 Shows **Veg dominance (~63%)**, indicating strong customer preference trends.

---

#### ⭐ Performance Overview KPIs (Sheet 2)
- **Average Rating:** 4.3 – High customer satisfaction  
- **Top Restaurant:** KFC – Highest performing brand  
- **Total Orders:** 197K+  

---

#### 🏆 Top 5 Restaurants by Revenue (Bar Chart)
Ranks restaurants by revenue.

👉 Identifies **key partners driving revenue** and **brand concentration**.

---

#### 📦 Orders by Category (Bar Chart)
Shows order volume across categories.

👉 Helps understand **demand distribution** and **category-level performance**.

---

### 🔹 Business Impact & Insights

- Revenue is concentrated in **top cities like Bengaluru**, indicating **geographic dependency**  
- Demand is driven by **few high-performing categories**, suggesting **product concentration risk**  
- Orders peak during **weekends**, highlighting **customer behavior patterns**  
- **Veg dominates revenue share**, indicating strong **customer preference trends**  
- Growth is primarily **volume-driven**, with moderate **Average Order Value (AOV)**  

---


## 🟦 6. Screenshots / Demo

### 📊 Revenue Drivers Dashboard  
![Revenue Drivers](./revenue_drivers_dashboard.png)

---

### 📊 Performance Overview  
![Performance Overview](./Performance_overview_dashboard.png) 



⭐ If you found this useful, feel free to star the repository!# food-delivery-revenue-analysis-excel-dashboard
 Interactive Excel dashboard analyzing food delivery revenue drivers across cities, categories, and customer behavior.
