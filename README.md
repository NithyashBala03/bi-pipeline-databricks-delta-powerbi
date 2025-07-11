__Scalable, near–real-time Business Intelligence pipeline for an Order Management System (OMS)__

OMS Business Intelligence Pipeline with Databricks, Delta Lake, and Power BI

This project demonstrates a **scalable, near–real-time Business Intelligence pipeline** for an **Order Management System (OMS)** using:

✅ **Databricks** (Spark and Delta Lake for data engineering)  
✅ **Structured Streaming** for ingestion  
✅ **Bronze, Silver, Gold architecture** for layered data refinement  
✅ **Power BI** for building interactive dashboards

---

## 🎯 **Business Problem**

E-commerce and logistics businesses often lack **real-time visibility** into:
- Order transactions
- Shipment statuses
- Inventory updates
- Customer insights

This results in:
❌ Delayed operational decisions  
❌ Manual, error-prone reporting  
❌ Missed opportunities for customer experience improvement

---

## 🧩 **Project Objective**

To build an **end-to-end, automated BI pipeline** that:
- Ingests **real-time and batch data** from OMS
- Cleans, validates, and enriches it across **Bronze → Silver → Gold layers**
- Enables **Power BI dashboards** for near-real-time operational monitoring
- Empowers business users with **self-service analytics**

---

## 📊 **Data Handled**

- **Orders** (order ID, product, quantity, timestamp, price)
- **Shipments** (status updates, delivery times)
- **Inventory** (stock levels, SKU statuses)
- **Customer metadata** (region, segments)

---

## 🛠️ **Solution Approach**

### 1️⃣ Data Ingestion
- Using **Databricks Autoloader and Spark Structured Streaming** for scalable ingestion into the **Bronze layer**.

### 2️⃣ Data Cleansing and Transformation
- Deduplication, schema enforcement, and enrichment in the **Silver layer**.

### 3️⃣ Aggregation for BI
- Creating customer segmentation, order volume, and SLA metrics in the **Gold layer**.

### 4️⃣ Visualization
- Connecting **Power BI** to Databricks Delta tables to create dashboards for:
  - Order trends
  - Shipment SLA monitoring
  - Inventory levels
  - Revenue tracking

