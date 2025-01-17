# 🚀 DoorDash Delivery Performance Dashboard

## 📖 Project Overview
This **Tableau Dashboard** provides insights into **DoorDash delivery performance**, focusing on **on-time delivery rates, order efficiency, and Dasher availability**. It helps stakeholders analyze **order trends, store performance, and delivery punctuality**.

---

## 📂 Data Sources
The dataset used in this project includes:
- **Historical DoorDash Order Data** (`Doordash.twb`)
- **Key Fields Used**:
  - `created_Date` - Order placement date
  - `created_time` - Time when the order was placed
  - `actual_delivery_time` - Time when the order was delivered
  - `Time_Duration(Mins)` - Total delivery time
  - `store_id` - Unique ID for stores
  - `store_primary_category` - Type of store (e.g., Italian, Mexican)
  - `total_items` - Number of items in the order
  - `subtotal` - Total order amount
  - `total_onshift_dashers` - Number of available dashers
  - `total_outstanding_orders` - Pending deliveries
  - `estimated_store_to_consumer_driving_duration` - Predicted delivery time

---

## 📊 Key Metrics (KPIs)
The dashboard tracks the following KPIs:
### 🚚 **Delivery Efficiency Metrics**
- **On-Time Delivery Rate**: % of deliveries completed within the estimated time.
- **Average Delivery Time**: Mean of `Time_Duration(Mins)`.
- **Late Deliveries**: Orders where `actual_delivery_time` > `estimated_store_to_consumer_driving_duration`.

### 🏪 **Store & Market Insights**
- **Top 5 Performing Stores** (Highest revenue from `subtotal`).
- **Orders per Store Category** (Comparing delivery efficiency).
- **Orders by Market** (Regional performance trends).

### 🚗 **Dasher Availability**
- **Dasher Supply vs. Order Demand** (`total_onshift_dashers` vs. `total_outstanding_orders`).
- **Peak Order Hours** (When the most orders are placed).

---

## 📈 Tableau Dashboard Components
### **1️⃣ Order Summary & KPIs**
- Displays **Total Orders, Revenue, Average Order Value, and On-Time Rate**.

### **2️⃣ Delivery Time Trends**
- **Line Chart**: Tracks delivery times over **days or hours**.
- **Heatmap**: Shows hourly order trends.

### **3️⃣ Market-Level Analysis**
- **Bar Chart**: Orders by `market_id`.
- **Pie Chart**: Breakdown of `store_primary_category`.

### **4️⃣ Dasher vs. Order Demand**
- **Dual-Axis Chart**: Compares `total_onshift_dashers` with `total_outstanding_orders`.

---

## 🔍 How to Use the Dashboard
1. **Load the `Doordash.twb` file** in Tableau.
2. **Filter Options**:
   - **Date Filter**: Select specific time ranges.
   - **Market Filter**: Analyze data by region.
   - **Store Type Filter**: Compare different categories (e.g., Fast Food vs. Fine Dining).
3. **Interact with the Charts**:
   - Hover to view details.
   - Click on bars or lines to drill down.

---

## 🛠️ Future Improvements
- 📌 **Predict Late Deliveries** using ML-based forecasting.
- 📌 **Optimize Dasher Allocation** by identifying peak-hour gaps.
- 📌 **Real-time Order Tracking** (If connected to live data).

---

## 📬 Contact
For any questions or contributions, feel free to reach out!

---
🚀 **Built with Tableau for Business Insights & Operational Optimization**
