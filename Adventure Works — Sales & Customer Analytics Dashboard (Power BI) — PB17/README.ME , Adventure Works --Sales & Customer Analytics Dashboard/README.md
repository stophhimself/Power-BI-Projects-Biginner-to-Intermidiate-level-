
# 🚴‍♂️ Adventure Works — Sales & Customer Analytics Dashboard (Power BI) — PB17

## 📌 Project Overview  
This Power BI dashboard analyzes **Adventure Works sales data** (a fictional multinational bike & outdoor equipment retailer), focusing on **product performance, customer segmentation, geographic distribution, profitability, and target achievement**.  

Designed as a **comprehensive business intelligence project**, it demonstrates **advanced DAX, time intelligence, customer analytics, and strategic storytelling** — ideal for showcasing analytical maturity in retail, e-commerce, or B2C operations.

---

## 👀 Dashboard Preview  
<img width="592" height="335" alt="Power BI - Adv 1" src="https://github.com/user-attachments/assets/df389b57-c5d3-434d-a2f6-0c3f5ba67850" /> 
<img width="588" height="326" alt="Power BI - Adv 2" src="https://github.com/user-attachments/assets/a3fccfd9-f016-465b-b605-1d10675712ec" />
<img width="592" height="328" alt="Power BI - Adv 3" src="https://github.com/user-attachments/assets/6d75b536-ec02-481c-bc85-b188797d70c1" />
<img width="593" height="332" alt="Power BI - Adv 4" src="https://github.com/user-attachments/assets/ae7f3d5b-a517-4196-a1ca-467402573d08" />




*(Screenshot captured January 27, 2026)*

---

## 🎯 Objectives  
- Analyze **company-wide KPIs**: revenue, profit, orders, return rate  
- Drill into **top-performing products** (e.g., *Water Bottle – 30 oz.*)  
- Compare **actual vs. target** (monthly orders, revenue, profit)  
- Segment customers by **income level, occupation, and geography**  
- Identify **top customers** and **most returned product types**  
- Practice **dashboard design, interactivity, and executive storytelling**

---

## 📊 Dashboard Breakdown

### 🔹 Key Metrics (KPIs)
- **Total Revenue**: $24.9M  
- **Total Profit**: $10.5M  
- **Total Orders**: 25.2K  
- **Return Rate**: 2.2%  
- **Unique Customers**: 17.4K  
- **Revenue per Customer**: $1,431  

→ Indicates **strong unit economics** and healthy repeat purchase behavior.

---

### 🔹 Product Deep Dive: *Water Bottle – 30 oz.*
- **Selected Product**: “Water Bottle – 30 oz.”  
- **Total Orders**: 404  
- **Revenue vs. Target**: $4,067 / $4,292 (**94.8%**)  
- **Profit vs. Target**: $2,546 / $2,687 (**94.8%**)  
- **Report Summary**:  
  > *“Total orders: 404 (+230.3% increase). Adjusted profit increased 230.3%. Trended up between Jun 28, 2021 and Jun 27, 2022.”*  
→ Shows **exceptional growth** for this high-margin accessory.

---

### 🔹 Monthly Performance vs. Targets
- **Gauge charts** for:
  - Monthly Orders vs. Target  
  - Monthly Revenue vs. Target  
  - Monthly Profit vs. Target  
- All show **~94–95% of target** → near-excellence, slight room for improvement  
- Line chart: **Total Profit vs. Adjusted Profit** over time (Jul 2021 – May 2022)  
  - Steady upward trend with seasonal peaks  
  - Adjusted profit consistently above total profit → strong margin control

---

### 🔹 Customer Insights
#### 📈 Total Customers & Revenue per Customer
- **17,4K unique customers**
- **$1,431 avg. revenue per customer** → high LTV potential

#### 🧾 Orders by Income Level
- **High Income (≥$100K)**: 2.8K customers (16%)  
- **Average Income ($50K–$100K)**: 11.6K (67%)  
- **Low Income (<$50K)**: 10.3K (59%)  
→ *Note: Overlap likely due to multi-year data; focus on % contribution.*

#### 👔 Orders by Occupation
- **Skilled Manual**: 6.0K  
- **Management**: 4.4K  
- **Professional**: 7.9K  
→ Confirms **B2C + B2B hybrid model** (e.g., corporate fleet purchases)

#### 🏆 Top 100 Customers Table
- **Mr. Maurice Shan**: $12,408 revenue (6 orders)  
- **Mrs. Janet Munoz**: $12,015  
- **Mrs. Lisa Cai**: $11,330  
- **Top Customer (by Revenue)**: **Mr. Maurice Shan**  
- **Top in Skilled Manual (2022)**: Ruben Suarez ($4,683)

---

### 🔹 Geographic Distribution
- **World Map** showing sales density by country:
  - **United States** (largest bubble)  
  - Canada, UK, Germany, France, Australia  
- Tabs: **Europe**, **North America**, **Pacific** → filterable  
→ Highlights **North America as core market**, with strong European presence

---

### 🔹 Product & Category Analysis
#### 📦 Orders by Category
- **Accessories**: 17.0K  
- **Bikes**: 13.9K  
- **Clothing**: 7.0K  
→ **Accessories drive volume**, bikes drive premium revenue

#### 🥇 Top 10 Products Table
| Product | Orders | Revenue | Return % |
|---------|--------|---------|----------|
| Water Bottle – 30 oz. | 3,983 | $39,755 | 1.95% |
| Patch Kit/8 Patches | 2,952 | $13,506 | 1.61% |
| Sport-100 Helmet, Red | 2,099 | $73,444 | **3.33%** ⚠️ |
| Sport-100 Helmet, Blue | 1,995 | $67,120 | **3.31%** ⚠️ |
| Mountain Bottle Cage | 1,896 | $38,062 | 2.02% |

→ **Helmets have highest return rates** — potential quality or fit issue.

#### 📉 Most Returned Product Type
- **Shorts** (highest return %)  
- **Tires and Tubes** (most ordered)  
→ Strategic insight: optimize sizing guidance or warranty for shorts.

---

## 📐 Methodology
- Data modeling: Star schema (`Sales` fact table + `Product`, `Customer`, `Date`, `Geography` dimensions)  
- DAX measures include:
  - `Total Revenue`, `Gross Profit`, `Return Rate`
  - `Adjusted Profit` (accounts for discounts/refunds)
  - `YoY Growth`, `MoM % Change`, `% of Target`
  - `Top Customer = SELECTEDVALUE(...) + TOPN(...)`
- Time intelligence using proper `Date` table  
- Interactive filters: Product, Region, Year, Occupation  
- Visual design: Clean dark theme with teal accents (Adventure Works branding)

---

## 🛠️ Tools & Technologies
- **Power BI Desktop**  
- **Intermediate–Advanced DAX** (CALCULATE, SUMX, TIMEINTELLIGENCE, TOPN, SELECTEDVALUE)  
- **Data visualization principles**: hierarchy, color coding, tooltips  
- **Dashboard layout**: Executive summary → drill-down → tactical insights  
- **Source**: Adventure Works sample database (Microsoft)

---

## 📌 Key Insights
✅ **$24.9M revenue with $10.5M profit** → **42.2% gross margin** (very healthy)  
✅ **Water Bottle – 30 oz.** is a breakout product: +230% growth, strong margin  
✅ **Accessories drive order volume**, but **bikes & helmets drive revenue**  
✅ **Return rate is low overall (2.2%)**, but **helmets & shorts are outliers**  
✅ **Top customers are high-value individuals** — opportunity for loyalty programs  
✅ **North America dominates**, but Europe shows strong potential  
✅ **Skilled Manual & Professional occupations** are key segments  

---

## 📁 Repository Structure
├── Adventure_Works_PB17.pbix
├── Dataset/
│ └── adventure_works_sales.csv # (or imported from SQL Server sample DB)
├── Screenshots/
│ └── adventure_works_pb17.png
└── README.md


---

## 🚀 Project Purpose
This project was built as a **portfolio Power BI project** to:  
- Practice **enterprise-grade retail analytics**  
- Improve **dashboard design and executive storytelling**  
- Apply **customer segmentation, product profitability, and target tracking**  
- Simulate **analytics reporting for global e-commerce brands**

---

## 📬 Contact
**Mustapha Tarfi**  
📍 Morocco  
🔗 LinkedIn: [https://www.linkedin.com/in/mustapha-tarfi-1106b5283/](https://www.linkedin.com/in/mustapha-tarfi-1106b5283/)  
