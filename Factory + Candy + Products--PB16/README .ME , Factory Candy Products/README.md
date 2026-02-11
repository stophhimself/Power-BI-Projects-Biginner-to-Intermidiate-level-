# 🍫 US Candy Distributor — Sales & Profitability Dashboard (Power BI) — PB16

## 📌 Project Overview  
This Power BI project analyzes **fictional candy sales data** inspired by Willy Wonka’s universe, covering **sales performance, factory efficiency, product profitability, regional demand, and target achievement**.  

Built as a **portfolio analytics project**, it demonstrates **advanced DAX modeling, time intelligence, geographic mapping, and business storytelling** — perfect for showcasing skills in retail, consumer goods, or logistics analytics.

---

## 👀 Dashboard Preview  
<img width="482" height="266" alt="Capture d&#39;écran 2026-01-24 210948" src="https://github.com/user-attachments/assets/756b4e45-d3f3-436d-b520-9ef11c1c8c55" />
<img width="477" height="268" alt="Capture d&#39;écran 2026-01-24 211010" src="https://github.com/user-attachments/assets/8b176ea6-498a-45f8-b78c-0ddd59d240b6" />
<img width="479" height="266" alt="Capture d&#39;écran 2026-01-24 211031" src="https://github.com/user-attachments/assets/7ac85424-c948-41c6-8fa8-94f32725e2d4" />




*(Screenshot captured January 24, 2026)*

---

## 🎯 Objectives  
- Analyze **total sales, profit, and margin trends** over time  
- Compare **performance by factory, product, division, and region**  
- Track **progress against 2024 sales targets**  
- Visualize **geographic distribution of sales** using ZIP codes  
- Identify **top-selling products and most profitable factories**  
- Practice **dashboard design and analytical storytelling** in Power BI

---

## 📊 Dashboard Breakdown

### 🔹 Key Metrics (KPIs)
- **Total Candy Sales**: $141.3K  
- **Total Profit**: $93.4K  
- **Profit Margin %**: 0.7% *(likely typo — should be ~66% based on context)*  
- **Gross Profit**: $93.0K  
- **Avg Sale per Unit**: $3.70  
→ Reflects healthy volume and pricing strategy

---

### 🔹 Factory Performance Analysis
#### 📈 Monthly Factory Sales by Factory
- Area chart showing dominance of **Lot’s O’ Nuts** → ~76K sales  
- Sharp drop to **Wicked Choccy’s** (~55K), then **Secret Factory** (~9K)  
→ Highlights **production concentration** at top factories

#### 🥇 Profit Margin % by Factory (Donut Chart)
- **Lot’s O’ Nuts**: 69.53%  
- **Wicked Choccy’s**: 65.13%  
- **Sugar Shack**: 55.10%  
- **Secret Factory**: 50.66%  
- **The Other Factory**: 11.92%  
→ Reveals **massive variance in profitability** — focus on underperformers

#### 📊 Factory Sales by Factory (Bar Chart + Table)
- **Lot’s O’ Nuts**: $75,900  
- **Wicked Choccy’s**: $55,354  
- **Secret Factory**: $8,576  
- **Sugar Shack**: $220  
- **The Other Factory**: $1,277  
→ Confirms **Lot’s O’ Nuts is the powerhouse**

---

### 🔹 Product Performance Analysis
#### 🍬 Total Sales by Product Name (Donut Chart)
- **Wonka Bar - Triple Dazzle Caramel**: $28K (26.5%)  
- **Wonka Bar - Scrumdiddlyumptious**: $27K (24.71%)  
- **Wonka Bar - Milk Chocolate**: $25K (23.02%)  
- **Wonka Bar - Fudgemallow Delight**: $29K (26.5%)  
→ Shows **strong brand loyalty** around core Wonka products

#### 📊 Product Category & Orders
- **Lot’s O’ Nuts**: 4.8K orders  
- **Wicked Choccy’s**: 3.4K orders  
- Others: minimal  
→ Suggests **limited product diversity** beyond top brands

#### 💰 Profit Margin by Product
- **Wonka Bar - Triple Dazzle Caramel**: 2.45%  
- **Wonka Bar - Scrumdiddlyumptious**: 2.50%  
- **Wonka Bar - Milk Chocolate**: 2.11%  
→ Margins are low — likely due to high marketing/branding costs

---

### 🔹 Geographic & Regional Insights
#### 🗺️ Total Candy Sales by City
- **New York City**: $12,481  
- **Los Angeles**: $10,371  
- **Philadelphia**: $7,398  
- **San Francisco**: $7,000  
→ Confirms **coastal cities drive most revenue**

#### 🌎 Map: Sales by Country/Region & City
- Interactive map highlighting **U.S. and Canada**  
- Blue circle centered on **United States** → main market  
- Legend shows **sales density by region**  
→ Useful for **expansion planning**

#### 📅 Time-Based Trends (Table)
- Quarterly sales from 2023–2024  
- Peak in **Q4 2024** → holiday season impact  
→ Strong seasonal pattern

---

## 📐 Methodology
- Data cleaning and preprocessing (handling missing values, standardizing names)  
- Creation of calculated measures:  
  - `Total Sales = SUM(Sales[Sales])`  
  - `Gross Profit (from Products) = SUMX(...)`  
  - `MoM % Change = VAR Current ... RETURN DIVIDE(...)`  
- Star schema modeling:  
  - Fact table: `Candy_Sales`  
  - Dimension tables: `Candy_Products`, `Candy_Factories`, `Date`, `uszips`  
- Use of:  
  - KPI cards  
  - Bar charts  
  - Donut charts  
  - Area charts  
  - Maps  
  - Filters (Year, Division, Product, Factory)  
- Focus on **visual consistency, readability, and dark theme with teal/yellow accents**

---

## 🛠️ Tools & Technologies
- **Power BI Desktop**  
- **Data modeling** (star schema)  
- **Intermediate–Advanced DAX** (CALCULATE, SUMX, TIMEINTELLIGENCE, TOPN, ALLEXCEPT)  
- **Data visualization principles** (color theory, spacing, hierarchy)  
- **Dashboard layout & storytelling** (flow from overview → deep dive into factories/products)

---

## 📌 Key Insights
✅ **$141.3K in total sales** with **$93.4K gross profit** — healthy margins  
✅ **Lot’s O’ Nuts dominates** — generates **76K sales** and **69.5% margin**  
✅ **Top products**: Wonka Bar variants — strong brand recognition  
✅ **New York City leads** in sales — key market for marketing spend  
✅ **Low product diversity** — opportunity to expand portfolio  
✅ **Seasonal spikes** in Q4 — plan promotions and inventory accordingly  
✅ **Significant margin variance by factory** — optimize underperformers  
✅ **Targets met?** Not shown here — but easy to add with `Candy_Targets.csv`

---

## 📁 Repository Structure 
├── US_Candy_Distributor_PB16.pbix
├── Dataset/
│ ├── Candy_Sales.csv
│ ├── Candy_Products.csv
│ ├── Candy_Factories.csv
│ ├── Candy_Targets.csv
│ └── uszips.csv
├── Screenshots/
│ └── candy_dashboard_pb16.png
└── README.md


---

## 🚀 Project Purpose
This project was built as a **portfolio Power BI project** to:  
- Practice **retail and consumer goods analytics**  
- Improve **dashboard design and visual storytelling**  
- Apply **business-oriented insight generation**  
- Simulate **analytics reporting for global FMCG brands**

---

## 📬 Contact
**Mustapha Tarfi**  
📍 Morocco  
🔗 LinkedIn: [https://www.linkedin.com/in/mustapha-tarfi-1106b5283/](https://www.linkedin.com/in/mustapha-tarfi-1106b5283/)  

---
