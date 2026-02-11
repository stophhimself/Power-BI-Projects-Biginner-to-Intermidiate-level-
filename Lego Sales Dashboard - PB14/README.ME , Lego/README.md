# 🧱 Lego Sales & Product Analysis Dashboard — PB14 (Power BI)

## 📌 Project Overview  
This project analyzes **LEGO product catalog data** using **Power BI**, with the objective of understanding **set distribution by category, theme group, age range, price, and piece count**.  

The dashboard is designed to showcase **data visualization, exploratory analysis, and storytelling skills**, using real-world toy/retail data — perfect for demonstrating commercial insight in the consumer goods and entertainment industry.

---

## 👀 Dashboard Preview  
<img width="575" height="313" alt="lego1&#39;&#39;&#39;&#39;" src="https://github.com/user-attachments/assets/d3e10265-f4b9-48b7-881a-5aa5258b248b" />
<img width="574" height="321" alt="lego2&#39;" src="https://github.com/user-attachments/assets/31cef801-5c70-4597-a28a-e479e1ea2db1" />


*(Screenshot captured January 15, 2026)*

---

## 🎯 Objectives  
- Analyze **total sets, average pieces, and average price**  
- Compare **sets by category, theme group, and theme**  
- Understand **product segmentation by age group and price tier**  
- Visualize **global set distribution via world map**  
- Explore **top sets by piece count and price**  
- Practice **dashboard design and analytical storytelling** in Power BI

---

## 📊 Dashboard Breakdown

### 🔹 Key Metrics (KPIs)
- **Total Sets**: 4,654  
- **Avg. Pieces per Set**: 411  
- **Avg. Price per Set**: $33  
→ Reflects LEGO’s broad product range — from small kits to large collectibles

---

### 🔹 Hierarchy Drilldown (Category → Theme Group → Theme → Name)
- Interactive funnel showing:  
  - **Total Sets**: 4,654  
    - **Normal**: 4,290  
    - **Gear**: 246  
    - **Extended**: 80  
  - Under **Normal**:  
    - **Licensed**: 1,283  
      - **Star Wars**: 388  
        - *Star Wars Advent Calendar*, *Imperial Star Destroyer*, *Millennium Falcon*  
      - **Marvel Super Heroes**: 156  
      - **BrickHeadz**: 104  
    - **Modern Day**: 725  
    - **Action/Adventure**: 551  
→ Reveals **Licensed themes dominate premium segments**, especially Star Wars

---

### 🔹 Filters Panel
- Dropdown filters for:  
  - **Theme Group** (Tout / Licensed / Modern day / Action/Adventure)  
  - **Theme** (Tout / Star Wars / Marvel / etc.)  
  - **Age Group** (Tout / 10–17 / Over 18 / etc.)  
- Slider for **Price Range** (e.g., up to $850)  
- Button: **Reset Filters** / **Explore Sets**

---

### 🔹 World Map Visualization
- Pixelated world map made of LEGO bricks → thematic branding  
- Shows **global set availability or popularity** (color-coded intensity)  
- Below map:  
  - **Year**: 2021  
  - **Pieces**: 11,70K (likely 11,700)  
  - **Age**: 18.00 (average recommended age?)  
→ Suggests **focus on adult collectors** and global reach

---

### 🔹 Top Sets Table
- List of high-end sets with:  
  - **Name**: World Map, Eiffel Tower, Titanic, Millennium Falcon, AT-AT, Taj Mahal  
  - **Set ID**  
  - **Theme**: Art, Icons, Star Wars, Creator Expert, Advanced  
  - **Age Range**: Over 18 or 10–17  
  - **Avg. Pieces**: 9,000+ for top sets  
  - **Price Range**: $$$$$ (highest tier)  
→ Highlights **premium, complex, collector-grade sets** as key revenue drivers

---

## 📐 Methodology
- Data cleaning and preprocessing (handling missing values, standardizing theme names)  
- Creation of calculated measures:  
  - `Avg Pieces = AVERAGE(Sets[Pieces])`  
  - `Avg Price = AVERAGE(Sets[Price])`  
  - `Total Sets = COUNTROWS(Sets)`  
- Hierarchical drilldown using **slicer + DAX path functions**  
- Use of:  
  - KPI cards  
  - Funnel/hierarchy charts  
  - World map (custom visual or image overlay)  
  - Table with conditional formatting (price tiers)  
  - Filters (Theme Group, Theme, Age Group)  
- Focus on **visual consistency, playful LEGO branding, and clean white/blue layout**

---

## 🛠️ Tools & Technologies
- **Power BI Desktop**  
- **Data modeling** (star schema implied)  
- **Basic–Intermediate DAX** (aggregations, hierarchies, conditional logic)  
- **Data visualization principles** (color theory, spacing, hierarchy)  
- **Dashboard layout & storytelling** (flow from overview → deep dive into premium sets)

---

## 📌 Key Insights
✅ **4,654 total sets** — vast catalog spanning multiple categories and themes  
✅ **Average set has 411 pieces and costs $33** — accessible entry point for most buyers  
✅ **Licensed themes (especially Star Wars)** dominate premium segments  
✅ **Top sets like World Map, Titanic, Millennium Falcon** have **9,000+ pieces** and **$$$$$ price tags** — target adult collectors  
✅ **Age group “Over 18”** appears frequently in top sets — strong focus on **adult fans (AFOLs)**  
✅ **World map visualization** reinforces global brand presence and product diversity  
✅ **Hierarchy drilldown** enables users to explore from broad categories down to individual sets

---

## 📁 Repository Structure

├── Lego_Sales_Dashboard_PB14.pbix
├── Dataset/
│ └── lego_sets_data.csv
├── Screenshots/
│ └── lego_dashboard_pb14.png
└── README.md

---

## 🚀 Project Purpose
This project was built as a **portfolio Power BI project** to:  
- Practice **consumer goods and toy industry analytics**  
- Improve **dashboard design and visual storytelling**  
- Apply **business-oriented insight generation**  
- Simulate **analytics reporting for brands like LEGO, Mattel, or Hasbro**

---

## 📬 Contact
**Mustapha Tarfi**  
📍 Morocco  
🔗 LinkedIn: [https://www.linkedin.com/in/mustapha-tarfi-1106b5283/](https://www.linkedin.com/in/mustapha-tarfi-1106b5283/)  
