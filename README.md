# ☕ Excel Dashboard: Coffee Shop Transaction Insights

## 📊 Project Overview
This project is built on a transactional dataset from multiple coffee shop locations, covering a six-month period (January to June). The dataset includes detailed information such as:

- Transaction dates and times  
- Quantities purchased  
- Store IDs and locations  
- Product categories and pricing  
- Revenue and time-based metadata (weekday and hour)  

The objective is to transform raw sales data into actionable insights that support **operational decisions**, **marketing efforts**, and **resource planning**. The dashboard is intended to serve as both a **daily decision-making tool** and a **strategic reference** during periodic business reviews.

---

## 🧱 Dashboard Structure

The dashboard is structured into three main sections:
1. **Top-level KPIs**
2. **Visual Insights**
3. **Interactive Heatmaps and Filters**

Each section is designed for both quick reference and deeper analytical dives depending on the user's role.

---

## 📌 Key Performance Indicators (KPIs)
The dashboard highlights the following dynamic KPIs:

- **Total Revenue:** Overall income across all transactions.
- **Total Transactions:** Number of unique transaction IDs.
- **Average Revenue per Transaction:** Revenue divided by the number of transactions.
- **Total Quantity Sold:** Total units sold (summed from `transaction_qty`).

These KPIs update automatically with filters like month, store, or product category, and are styled for easy reading using icons, colors, and formatting.

---

## 📍 Visual Insights

### 🏪 Location Insights
- **Slicer by Store Location**  
- **Bar Charts for Revenue and Transactions by Store**  
  - *Example Insight:* Hell’s Kitchen location has the highest revenue.

**Potential Revenue Gaps & Solutions**:
- Lower-performing locations may suffer from poor foot traffic, competition, or staff performance.
  - 🔧 **Solutions:**
    - Analyze foot traffic patterns.
    - Use location-based promotions.
    - Share best practices from top-performing stores.

---

### 📦 Product Analysis
- **Stacked Column Chart:**
  - Transactions by Product Category
  - Top-selling Product Types

**Example Insight:** Barista Espresso products generate high revenue and strong margins.

---

### ⏰ Time-Based Patterns
- **Line Chart: Revenue by Month**
  - *Insight:* February dip likely due to post-holiday financial fatigue.
- **Clustered Bar Charts:**
  - Transactions by Day of Week
  - Transactions by Hour

**Friday High Sales:**
- Customers indulge ahead of weekends
- Salary/payday cycles may influence buying

**Sunday Low Sales:**
- Reduced commuting and footfall

---

### 🔥 Heatmap: “When Are We Busiest?”
- **Heatmap: Revenue by Hour vs Weekday**
  - Shows intensity of sales across the week
  - Peak time: **7 AM – 10 AM on weekdays**

**Applications:**
- Staff scheduling
- Promotional timing
- Inventory prep

---

## 🎯 Conclusion

This dashboard delivers an interactive and visually engaging overview that helps:

1. **Improve Operational Efficiency**
2. **Support Marketing & Sales Strategy**
3. **Monitor Performance in Real Time**

---

## 📌 Recommendations
- **Increase Staffing**: Weekday mornings (7–10 AM)
- **Boost Midweek Marketing**: Target underperforming days
- **Bundle/Upsell in Busy Stores**: Drive revenue per customer
- **Customize Stock by Location**: Match products to demand

---

## 📝 Files Included
- Excel dashboard with slicers and dynamic visuals
- Project summary (.docx) detailing insights and methodology

---

## 💡 Author Note
This project demonstrates the power of transforming raw transactional data into a decision-support tool using Excel’s built-in visualization and analysis capabilities.

---

© 2025 Michael Konadu Ansong. 
All rights reserved.
