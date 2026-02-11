# 🎮 Pokémon — Statistical Analysis Dashboard (Power BI)

## 📌 Project Overview  
This project analyzes the **Pokémon dataset** using **Power BI**, with the objective of understanding **Pokémon distribution by type, generation, legendary status, stats (attack/defense), and dual-type prevalence**.  

The dashboard is designed to showcase **data visualization, exploratory analysis, and storytelling skills**, using a globally recognized pop-culture dataset — perfect for demonstrating analytical thinking in a fun, engaging context.

---

## 👀 Dashboard Preview  
<img width="379" height="214" alt="Capture d&#39;écran 2026-01-09 110745" src="https://github.com/user-attachments/assets/bc7cbedb-776a-45d1-8fbe-c0233e4ed165" />
 
*(Screenshot captured January 9, 2026)*

---

## 🎯 Objectives  
- Analyze the **total number of Pokémon** and their **legendary status**  
- Compare **Pokémon by generation**  
- Identify **most common types** and their average stats  
- Visualize **attack vs defense correlation**  
- Explore **dual-type prevalence** and **stat trends**  
- Practice **dashboard design and analytical storytelling** in Power BI

---

## 📊 Dashboard Breakdown

### 🔹 Key Metrics (KPIs)
- **Total Pokémon**: 721  
- **Total Legendary**: 65  
- **Dual Type Count**: 414  
- **Average of Total Stats**: 435.10  
- **Generation Filter**: Available (Tout / Générations 1–6)

---

### 🔹 Total Legendary Analysis
- Donut chart showing:  
  - **Legendary**: 8.13% (65 Pokémon)  
  - **Non-Legendary**: 91.88% (656 Pokémon)  
→ Highlights the **rarity and exclusivity** of legendary Pokémon

---

### 🔹 Total Pokémon by Generation
- Bar chart showing Pokémon count per generation:  
  - Gen 1: 166  
  - Gen 2: 106  
  - Gen 3: 160  
  - Gen 4: 121  
  - Gen 5: 165  
  - Gen 6: 82  
→ Reveals **fluctuations in release size** — peak in Gen 1 & 5, drop in Gen 6

---

### 🔹 Attack vs Defense Scatter Plot
- Scatter plot visualizing **Attack vs Defense** for all Pokémon  
- Dense cluster around mid-range stats → most Pokémon are **balanced**  
- Outliers show **high-attack or high-defense specialists**  
→ Useful for team-building strategies and game balance analysis

---

### 🔹 Total Pokémon by Type 1
- Horizontal bar chart showing count per primary type:  
  - Water: 112  
  - Normal: 98  
  - Grass: 70  
  - Bug: 69  
  - ...and more  
→ Confirms **Water and Normal as dominant types** in early generations

---

### 🔹 Average of Total by Type 1
- Bar chart showing **average total stats per type**:  
  - Dragon: 550.53  
  - Steel: 487.70  
  - Flying: 475.95  
  - Psychic: 453.75  
  - ...down to Bug: 378.93  
→ Shows **Dragon-type Pokémon are statistically strongest**, while **Bug-types are weakest on average**

---

### 🔹 Dual Type Prevalence
- KPI card: **414 Pokémon are dual-typed**  
→ Indicates that **over half** of all Pokémon have hybrid typing — key for strategic depth in battles

---

## 📐 Methodology
- Data cleaning and preprocessing (handling missing values, standardizing types)  
- Creation of calculated measures:  
  - `Total Legendary = COUNTROWS(FILTER(Pokémon, Pokémon[Legendary] = "True"))`  
  - `Average Total Stats = AVERAGE(Pokémon[Total])`  
- Time-based aggregation (generation grouping)  
- Use of:  
  - KPI cards  
  - Bar charts  
  - Scatter plots  
  - Donut charts  
  - Filters (Generation, Legendary)  
- Focus on **visual consistency, readability, and Pokémon-themed color palette**

---

## 🛠️ Tools & Technologies
- **Power BI Desktop**  
- **Data modeling** (star schema implied)  
- **Basic–Intermediate DAX** (aggregations, filters, conditional logic)  
- **Data visualization principles** (color theory, spacing, hierarchy)  
- **Dashboard layout & storytelling** (flow from overview → deep dive)

---

## 📌 Key Insights
✅ **721 Pokémon total**, with **65 legendary** — ~8% rarity rate  
✅ **Generation 1 and 5 had the most releases**; Gen 6 was smallest  
✅ **Water and Normal are most common types** — reflects early game design  
✅ **Dragon-type Pokémon have highest average stats** — powerhouses in battle  
✅ **Over half are dual-typed** — adds complexity and strategy to gameplay  
✅ **Attack and Defense are moderately correlated** — balanced but with specialist outliers

---

## 📁 Repository Structure
├── Pokemon_Dashboard.pbix
├── Dataset/
│ └── pokemon_data.csv
├── Screenshots/
│ └── pokemon_dashboard.png
└── README.md


---

## 🚀 Project Purpose
This project was built as a **portfolio Power BI project** to:  
- Practice **exploratory data analysis** with a fun, popular dataset  
- Improve **dashboard design and visual storytelling**  
- Apply **business-oriented insight generation** (even in gaming contexts)  
- Simulate **analytics reporting for entertainment/gaming industries**

---

## 📬 Contact
**Mustapha Tarfi**  
📍 Morocco  
🔗 LinkedIn: [https://www.linkedin.com/in/mustapha-tarfi-1106b5283/](https://www.linkedin.com/in/mustapha-tarfi-1106b5283/)  
