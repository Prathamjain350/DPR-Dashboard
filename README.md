# 📊 Power BI Dashboard: DPR (Daily Production Report)
---

## 📌 Overview
This *Power BI Dashboard* provides a *Daily Production Report (DPR)* along with insights into wastage, production changes, and shipment performance across platforms.  

It enables stakeholders to:  
- Monitor daily production output  
- Track wastage patterns & efficiency  
- Compare shipment metrics across e-commerce platforms  
- Analyze production trends (Daily, Monthly, Quarterly, Yearly)  

---

## 🎯 Key Objectives
- Provide a single consolidated view of *production KPIs*  
- Reduce *material wastage* by identifying inefficiencies  
- Enable *real-time decision-making* with daily refreshed data  
- Support *cross-platform shipment analysis* (Amazon, Flipkart, Myntra, Blinkit)

---
🌐 Live Power BI Dashboard

You can explore the interactive Power BI dashboard here 👇 👉 https://app.powerbi.com/groups/me/reports/6976f68b-2b9e-47b4-958e-cd09a169b95b/7004e1b2f46451e6e16f?experience=power-bi

---

## 📂 Report Structure (Pages)

### 1. *DPR (Daily Production Report)*
- Cutting, Stitching, Pressing, Thread Cutting outputs  
- Tailor presence & productivity  
- Packed Qty & Achievement %  
- Output comparison by *Floor* and *Stage*  
- Drill-down by Product Family  

### 2. *Wastage Insights*
- Issued vs Used Quantity  
- Cutting Output vs Eyelet Wastage  
- Good Usage vs Wastage Pie Analysis  
- Fabric Wastage Trend over time  

### 3. *Changes Overview*
- Production YTD (Year-To-Date)  
- Production QTD (Quarter-To-Date)  
- Production MTD (Month-To-Date)  
- Daily Production Trends  

### 4. *Shipment Overview*
- Shipment comparison across *Amazon, Flipkart, Myntra, Blinkit*  
- Total Shipments vs Previous Month  
- Pending Shipments overview  

---

## 📊 Highlighted Metrics
| Metric | Description |
|--------|-------------|
| *Cutting Qty* | Number of items cut in production |
| *Stitched Qty* | Items stitched successfully |
| *Wastage %* | Fabric/material wastage ratio |
| *Achievement %* | Performance vs target |
| *Eyelet Wastage* | Total wastage from eyelet process |
| *Pending Shipments* | Orders awaiting dispatch |
| *Platform Shipments* | Amazon, Flipkart, Myntra, Blinkit stats |

---

## 🛠 Technical Details
- *Platform*: Power BI Service  
- *Data Sources*: Excel/CSV (production logs & shipment data)  
- *Data Model*: Star Schema with Fact tables (Fact_Production, Fact_Shipment) and Dim tables (Dim_Product, Dim_Floor, Dim_Date)  
- *Refresh Schedule*: Daily  
- *Row-Level Security (RLS)*: Implemented by Floor
- 
---

## 👤 Author
 Pratham Jain

⭐ If you find this dashboard inspiring, consider giving this repo a *star*!
