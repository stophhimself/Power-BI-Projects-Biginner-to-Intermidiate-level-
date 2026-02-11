# 🚗 Cars Sales Performance Dashboard — Power BI

## 📌 Project Overview  
This project analyzes **automotive sales data** using **Power BI**, with the objective of understanding **revenue trends, vehicle performance by make/model, pricing strategies, condition impact, and buyer preferences by color, body type, and transmission**.  

The dashboard is designed to showcase **data visualization, exploratory analysis, and business storytelling skills**, using real-world car dealership or marketplace data — perfect for demonstrating commercial insight in the automotive industry.

---

## 👀 Dashboard Preview  
<img width="578" height="329" alt="Capture d&#39;écran 2026-01-11 201446" src="https://github.com/user-attachments/assets/683aae32-1793-480d-a408-fb273b4f0eff" />

*(Screenshot captured January 11, 2026)*

---

## 🎯 Objectives  
- Analyze **total sales revenue, units sold, and average selling price**  
- Compare **sales by car make, body type, and color**  
- Understand **pricing trends by transmission (manual vs automatic)**  
- Visualize **sales over time (2014–2015)**  
- Explore **condition vs price correlation**  
- Practice **dashboard design and analytical storytelling** in Power BI

---

## 📊 Dashboard Breakdown

### 🔹 Key Metrics (KPIs)
- **Total Sales Revenue**: $2M  
- **Total Cars Sold**: 93K  
- **Avg Selling Price**: $17,62K  
- **Avg Odometer**: 37,12K miles  
- **Avg Condition**: 35.36 (scale likely 0–100)  
- **MMR Variance**: $12M *(likely Market Value vs Actual Sale Price difference)*

---

### 🔹 Sales Revenue by Make  
- Horizontal bar chart showing top manufacturers:  
  - Ford: **$0.36M**  
  - Nissan: **$0.32M**  
  - BMW: **$0.16M**  
  - Mercedes-Benz: **$0.15M**  
  - Chevrolet: **$0.12M**  
→ Highlights **Ford and Nissan as top revenue generators**

---

### 🔹 Selling Price vs Odometer  
- Scatter plot showing relationship between **price and mileage**  
- Clear downward trend → higher odometer = lower price  
- Color-coded by body type (Convertible, Coupe, Crew Cab, etc.)  
→ Useful for **pricing strategy and valuation models**

---

### 🔹 Cars Sold by Body Type  
- Horizontal bar chart showing:  
  - Sedan: **$0.58M**  
  - SUV: **$0.38M**  
  - Coupe: **$0.05M**  
  - Hatchback: **$0.04M**  
  - Convertible: **$0.04M**  
  - SuperCrew: **$0.03M**  
→ Confirms **Sedans dominate revenue**, followed by SUVs — key for inventory planning

---

### 🔹 Cars Sold by Color – Top 10  
- Bar chart showing most popular colors:  
  - Black: **20K**  
  - White: **19K**  
  - Gray: **16K**  
  - Silver: **12K**  
  - Red: **7K**  
  - Blue: **7K**  
  - Green: **7K**  
  - Beige: **1K**  
  - Gold: **1K**  
→ Reveals **black and white as top choices** — important for stock allocation

---

### 🔹 Average Selling Price by Transmission  
- Donut chart showing:  
  - Manual: **$18,01K (34%)**  
  - Automatic: **$17,68K (33.37%)**  
  - Unknown/Other: **$17,29K (32.64%)**  
→ Slight edge to **manual transmissions** in average price — may reflect performance models

---

### 🔹 Condition vs Average Price  
- Bar chart showing median selling price by condition score (0–100 scale)  
- Higher condition = higher price → strong positive correlation  
→ Validates that **vehicle condition directly impacts resale value**

---

### 🔹 Top 10 Sellers by Revenue  
- Horizontal bar chart showing top dealerships/sellers:  
  - Ford Motor Credit: **$0.32M**  
  - Nissan-Infiniti IT: **$0.26M**  
  - The Hertz Corp.: **$0.24M**  
  - Nissan Infiniti IT: **$0.20M**  
→ Highlights **major players in used car sales** — useful for partnership or competitive analysis

---

### 🔹 Sales Trend Over Time  
- Line chart tracking total sales revenue from **2014 to 2015**  
- Steady upward trend → growth in sales volume or pricing  
→ Indicates **positive market momentum** during this period

---

### 🔹 Average Selling Price by Make  
- Horizontal bar chart showing average price per brand:  
  - BMW: **$29K**  
  - Mercedes-Benz: **$28K**  
  - Ford: **$17K**  
  - Chevrolet: **$16K**  
  - Dodge: **$14K**  
→ Confirms **luxury brands command premium prices**, while mainstream brands are more affordable

---

## 📐 Methodology
- Data cleaning and preprocessing (handling missing values, standardizing makes/colors)  
- Creation of calculated measures:  
  - `Avg Selling Price = AVERAGE(Sales[Price])`  
  - `MMR Variance = SUM(Sales[MarketValue] - Sales[ActualPrice])`  
- Time-based aggregation (yearly trends)  
- Use of:  
  - KPI cards  
  - Bar charts  
  - Scatter plots  
  - Donut/pie charts  
  - Line charts  
  - Filters (Make, Body Type, Transmission)  
- Focus on **visual consistency, readability, and neutral color palette (grayscale + blue accents)**

---

## 🛠️ Tools & Technologies
- **Power BI Desktop**  
- **Data modeling** (star schema implied)  
- **Basic–Intermediate DAX** (aggregations, ratios, time intelligence)  
- **Data visualization principles** (color theory, spacing, hierarchy)  
- **Dashboard layout & storytelling** (flow from overview → deep dive)

---

## 📌 Key Insights
✅ **$2M in total revenue** from **93K cars sold** — healthy volume and pricing  
✅ **Ford and Nissan lead in revenue**, while **BMW and Mercedes lead in average price**  
✅ **Sedans generate highest revenue**, followed by SUVs — prioritize inventory accordingly  
✅ **Black and white are most popular colors** — align stock with buyer preferences  
✅ **Higher condition = higher price** — validates inspection and grading systems  
✅ **Manual transmissions slightly more expensive** — may reflect performance or niche appeal  
✅ **Sales grew steadily from 2014 to 2015** — positive market trend  
✅ **Top sellers**: Ford Motor Credit, Nissan-Infiniti, Hertz — key partners or competitors

---

## 📁 Repository Structure

├── Cars_Sales_Dashboard.pbix
├── Dataset/
│ └── cars_sales_data.csv
├── Screenshots/
│ └── cars_sales_dashboard.png
└── README.md


---

## 🚀 Project Purpose
This project was built as a **portfolio Power BI project** to:  
- Practice **automotive retail analytics**  
- Improve **dashboard design and visual storytelling**  
- Apply **business-oriented insight generation**  
- Simulate **analytics reporting for car dealerships, marketplaces, or OEMs**

---

## 📬 Contact
**Mustapha Tarfi**  
📍 Morocco  
🔗 LinkedIn: [https://www.linkedin.com/in/mustapha-tarfi-1106b5283/](https://www.linkedin.com/in/mustapha-tarfi-1106b5283/)  
