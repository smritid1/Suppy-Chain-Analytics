# Supply Chain Analytics Dashboard (Tableau & Power BI)

## Project Overview
This project focuses on analyzing **supply chain performance**, particularly shipment delays and inventory management, using **Tableau** and **Power BI**.

The goal was to identify inefficiencies, uncover trends, and provide actionable insights to improve business operations and decision-making.

---

## 🎯 Objectives
- Analyze shipment delays and trends over time  
- Evaluate inventory performance (overstock vs understock)  
- Understand supply-demand mismatches  
- Identify problematic product categories  
- Build interactive dashboards for stakeholders  

---

## 🛠️ Tools & Technologies
- Tableau  
- Power BI  
- Excel / CSV  

---

## 📂 Dataset Description
- **Orders & Shipments** → Order details and shipment timing  
- **Inventory** → Stock levels and storage costs  
- **Fulfillment** → Restocking lead times  

---

## 📊 Key KPIs & Calculations

### Shipment Delay

Shipment Delay (days) = Shipment Days (Actual) - Shipment Days (Scheduled)


### Delay Categories
- Before schedule → delay < 0  
- On schedule → delay = 0  
- Delay up to 5 days → delay ≤ 5  
- Delay over 5 days → delay > 5  

### Delayed Orders Ratio

Delayed Orders / Total Orders


### Inventory to Sales Delta

Warehouse Inventory - Order Quantity


### Overstock / Understock
- Positive → Overstock  
- Negative → Understock  

### Monthly Cost Impact

Average Over/Understock × Inventory Cost Per Unit


---

## 🔍 Key Findings

### 🚚 Shipment Insights
- High percentage of delayed shipments overall  
- Shipment performance improved over time  
- March 2016 was the last month with consistently high delays  
- January 2015 had the highest delays (>5 days)  
- Delay peak observed in October 2017  
- Last 3 months show unusually low order volume → possible data reliability issue  
- Overall improvement may be misleading without volume context  

---

### 📦 Inventory Insights
- Major challenges in inventory optimization  
- Significant overstock and understock situations  
- Overstock leads to high storage costs and waste  
- Understock leads to missed sales and delayed orders  
- Women’s Apparel shows major supply-demand imbalance  
- Only a few product categories operate at ideal inventory levels  

---

### 📊 Demand & Sales Trends
- Highest monthly order quantity ≈ 2.3K  
- Order volume relatively stable except for last 3 months anomaly  

---

### 🛒 Product Category Insights
- Cleats category has the highest excess supply over demand  
- Many categories fall outside optimal inventory balance  

---

## ⚠️ Key Problems Identified

### 1. Shipment Issues
- Frequent delays  
- External disruptions (logistics, freight, delivery issues)  

### 2. Inventory Problems
- Overstock → high holding costs  
- Understock → lost revenue and poor customer experience  

### 3. Data Issues
- Low order counts in recent months  
- Risk of misleading insights when using percentages only  

---

## 💡 Recommendations

### Inventory Optimization
- Implement Just-in-Time (JIT) inventory strategy  
- Improve demand forecasting  
- Set dynamic reorder points  

### Shipment Improvement
- Reduce lead times  
- Improve logistics coordination  
- Monitor delay trends continuously  

### Data Strategy
- Always compare percentages with actual volumes  
- Investigate anomalies in data  
- Build alert systems for unusual patterns  

### Business Strategy
- Focus on problematic categories like Women’s Apparel  
- Align supply with real demand  
- Reduce dependency on unstable supply chains  

---

## 📊 Dashboards

### Shipment Dashboard
- Shipment delay trends  
- Delay distribution  
- KPI metrics  

### Inventory Dashboard
- Overstock vs Understock analysis  
- Supply vs Demand trends  
- Category-level insights  

---

## 📌 Conclusion
This project demonstrates how data analytics can uncover inefficiencies in supply chains.

By optimizing inventory and improving shipment processes, businesses can:
- Reduce costs  
- Improve customer satisfaction  
- Increase operational efficiency  

---

## 👤 Author
**Radhakrishna**  
Data Analyst | Tableau & Power BI Enthusiast  

---

## 🔗 LinkedIn Post

🚀 Just completed my Supply Chain Analytics project using Tableau & Power BI!

In this project, I analyzed shipment delays and inventory performance to uncover key business insights:

📦 Inventory Issues  
- Overstock & understock across multiple categories  
- Women’s Apparel shows major imbalance  

🚚 Shipment Insights  
- High delays initially, improving over time  
- Peak delays in Jan 2015 & Oct 2017  

📊 Key Learnings  
- Percentages can be misleading without volume context  
- Demand forecasting is critical  

💡 Recommendations  
- Implement Just-in-Time inventory  
- Improve logistics coordination  
- Use data-driven forecasting  

This project strengthened my skills in Tableau, Power BI, and supply chain analytics.

#DataAnalytics #Tableau #PowerBI #SupplyChain #BusinessIntelligence
You have broken down. Give me file so I can copy and paste in one go.
# 📦 Supply Chain Analytics Dashboard (Tableau & Power BI)

## 📌 Project Overview
This project focuses on analyzing **supply chain performance**, particularly shipment delays and inventory management, using **Tableau** and **Power BI**.

The goal was to identify inefficiencies, uncover trends, and provide actionable insights to improve business operations and decision-making.

---

## 🎯 Objectives
- Analyze shipment delays and trends over time  
- Evaluate inventory performance (overstock vs understock)  
- Understand supply-demand mismatches  
- Identify problematic product categories  
- Build interactive dashboards for stakeholders  

---

## 🛠️ Tools & Technologies
- Tableau  
- Power BI  
- Excel / CSV  

---

## 📂 Dataset Description
- **Orders & Shipments** → Order details and shipment timing  
- **Inventory** → Stock levels and storage costs  
- **Fulfillment** → Restocking lead times  

---

## 📊 Key KPIs & Calculations

### Shipment Delay
```
Shipment Delay (days) = Shipment Days (Actual) - Shipment Days (Scheduled)
```

### Delay Categories
- Before schedule → delay < 0  
- On schedule → delay = 0  
- Delay up to 5 days → delay ≤ 5  
- Delay over 5 days → delay > 5  

### Delayed Orders Ratio
```
Delayed Orders / Total Orders
```

### Inventory to Sales Delta
```
Warehouse Inventory - Order Quantity
```

### Overstock / Understock
- Positive → Overstock  
- Negative → Understock  

### Monthly Cost Impact
```
Average Over/Understock × Inventory Cost Per Unit
```

---

## 🔍 Key Findings

### 🚚 Shipment Insights
- High percentage of delayed shipments overall  
- Shipment performance improved over time  
- March 2016 was the last month with consistently high delays  
- January 2015 had the highest delays (>5 days)  
- Delay peak observed in October 2017  
- Last 3 months show unusually low order volume → possible data reliability issue  
- Overall improvement may be misleading without volume context  

---

### 📦 Inventory Insights
- Major challenges in inventory optimization  
- Significant overstock and understock situations  
- Overstock leads to high storage costs and waste  
- Understock leads to missed sales and delayed orders  
- Women’s Apparel shows major supply-demand imbalance  
- Only a few product categories operate at ideal inventory levels  

---

### 📊 Demand & Sales Trends
- Highest monthly order quantity ≈ 2.3K  
- Order volume relatively stable except for last 3 months anomaly  

---

### 🛒 Product Category Insights
- Cleats category has the highest excess supply over demand  
- Many categories fall outside optimal inventory balance  

---

## ⚠️ Key Problems Identified

### 1. Shipment Issues
- Frequent delays  
- External disruptions (logistics, freight, delivery issues)  

### 2. Inventory Problems
- Overstock → high holding costs  
- Understock → lost revenue and poor customer experience  

### 3. Data Issues
- Low order counts in recent months  
- Risk of misleading insights when using percentages only  

---

## 💡 Recommendations

### Inventory Optimization
- Implement Just-in-Time (JIT) inventory strategy  
- Improve demand forecasting  
- Set dynamic reorder points  

### Shipment Improvement
- Reduce lead times  
- Improve logistics coordination  
- Monitor delay trends continuously  

### Data Strategy
- Always compare percentages with actual volumes  
- Investigate anomalies in data  
- Build alert systems for unusual patterns  

### Business Strategy
- Focus on problematic categories like Women’s Apparel  
- Align supply with real demand  
- Reduce dependency on unstable supply chains  

---

## 📊 Dashboards

### Shipment Dashboard
- Shipment delay trends  
- Delay distribution  
- KPI metrics  

### Inventory Dashboard
- Overstock vs Understock analysis  
- Supply vs Demand trends  
- Category-level insights  

---

## 📌 Conclusion
This project demonstrates how data analytics can uncover inefficiencies in supply chains.

By optimizing inventory and improving shipment processes, businesses can:
- Reduce costs  
- Improve customer satisfaction  
- Increase operational efficiency  

---

## 👤 Author
**Radhakrishna**  
Data Analyst | Tableau & Power BI Enthusiast  

---

## 🔗 LinkedIn Post

🚀 Just completed my Supply Chain Analytics project using Tableau & Power BI!

In this project, I analyzed shipment delays and inventory performance to uncover key business insights:

📦 Inventory Issues  
- Overstock & understock across multiple categories  
- Women’s Apparel shows major imbalance  

🚚 Shipment Insights  
- High delays initially, improving over time  
- Peak delays in Jan 2015 & Oct 2017  

📊 Key Learnings  
- Percentages can be misleading without volume context  
- Demand forecasting is critical  

💡 Recommendations  
- Implement Just-in-Time inventory  
- Improve logistics coordination  
- Use data-driven forecasting  

This project strengthened my skills in Tableau, Power BI, and supply chain analytics.

#DataAnalytics #Tableau #PowerBI #SupplyChain #BusinessIntelligence
