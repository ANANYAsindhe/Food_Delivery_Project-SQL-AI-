# Food_Delivery_Project-SQL-AI-

# 🍽️ Online Food Delivery Business Analytics System

## 📊 SQL & Business Analytics Capstone Project

This project analyzes food delivery platform data to uncover actionable business insights related to revenue performance, customer behavior, restaurant efficiency, delivery operations, and discount effectiveness.

Inspired by real-world platforms like **Swiggy, Zomato, and Uber Eats**.

---

## 🚀 Project Objectives

✔ Analyze revenue trends and city performance  
✔ Segment customers based on spending behavior  
✔ Evaluate restaurant performance & ratings  
✔ Monitor delivery efficiency and delays  
✔ Assess payment methods & discount impact  
✔ Enable data-driven decision making  

---

## 🗂 Dataset Overview

The project uses five relational tables:

- **Customers** – demographics & customer info  
- **Restaurants** – cuisine, ratings & locations  
- **Orders** – transactions, payments & delivery time  
- **Order_Items** – item-level details  
- **Delivery_Agents** – delivery partner data  

---

## 🧩 Database Structure

The **Orders table** acts as the central entity linking:

Customers → Orders ← Restaurants  
Orders → Order_Items  
Delivery Agents → Orders  

---

## 🔍 Analysis Performed

### 📈 Exploratory Data Analysis
- Total revenue calculation  
- Orders per city  
- Top customers by spending  

### 👥 Customer Segmentation
- Gold (> ₹5000)
- Silver (₹2000–₹5000)
- Bronze (< ₹2000)

### 🍽 Restaurant Performance
- Top restaurants by revenue  
- Rating vs revenue insights  

### 🚚 Delivery Performance
- Average delivery time by city  
- Late deliveries (>45 minutes)

### 💳 Payment & Discount Analysis
- Payment method distribution  
- Discount impact on revenue  

---

## 🧠 Advanced SQL Implementation

✔ Monthly revenue trend using CTE  
✔ Restaurant ranking using window functions  
✔ Above-average revenue analysis  

---

## ⚙️ Database Optimization & Automation

### Views & Stored Procedures
- Revenue view for reporting
- Stored procedure: Top N restaurants

### Indexing
- order_date
- customer_name
- restaurant_name

### Trigg​​ers
- Prevent negative discounts
- Delivery delay alerts

---

## 📊 Dashboard & Visualizations

The dashboard includes:

- KPI Cards (Revenue & Orders)
- Revenue by City
- Monthly Revenue Trend
- Payment Method Distribution
- Delivery Time Insights

---

## 🔑 Key Insights

✅ Revenue concentrated in major cities  
✅ High-value customers drive profits  
✅ Higher ratings improve restaurant revenue  
✅ Delivery delays affect customer satisfaction  
✅ Discounts increase order volume  

---

## 📌 Business Recommendations

✔ Implement loyalty programs for premium customers  
✔ Improve logistics in delay-prone cities  
✔ Promote top-performing restaurants  
✔ Optimize discount strategies  

---

## 🛠 Tools & Technologies

- SQL (MySQL / SQLite)
- Python (Pandas, Matplotlib)
- Power BI (Dashboard design)
- Jupyter Notebook

---

## 📚 Future Enhancements

- AI demand forecasting  
- Real-time analytics dashboards  
- Delivery route optimization  
- Recommendation systems  

---

## 👩‍💼 Author

**Ananya Sindhe**  
MBA Business Analytics  

---

⭐ If you found this project useful, feel free to star the repo!
