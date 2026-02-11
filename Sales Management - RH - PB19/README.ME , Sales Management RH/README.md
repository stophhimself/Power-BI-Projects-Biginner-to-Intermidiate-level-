# 📊 Sales-Management-HR Dashboard — PB19

## 📌 Project Overview  
This Power BI dashboard analyzes **sales, service, and human resources data** for a Moroccan telecommunications company (e.g., “Contoso Telecom” or fictional provider), focusing on **regional performance, service profitability, customer abandonment, and workforce demographics**.  

Designed as a **cross-functional business intelligence project**, it demonstrates **integrated reporting across Sales, Service, and HR**, using real-world operational data — ideal for showcasing analytical maturity in telecom, SaaS, or B2C service industries.

---

## 👀 Dashboard Preview  
<img width="611" height="344" alt="Sales RH 1" src="https://github.com/user-attachments/assets/41849fba-0d28-4488-8852-347d920c2602" /> 
<img width="604" height="344" alt="Sales RH 2 " src="https://github.com/user-attachments/assets/bc383cd0-ca4f-4957-b229-94765d0f18af" /> 
<img width="599" height="339" alt="Sales RH 3 " src="https://github.com/user-attachments/assets/d4b0eb21-5f33-4687-9a54-2f8129442144" />




---

## 🎯 Objectives  
- Analyze **revenue and service volume by city and service type**  
- Track **customer abandonment rates by service/subscription tier**  
- Compare **sales rep distribution, age, and salary by city**  
- Visualize **service pricing vs. acquisition cost**  
- Practice **multi-tab dashboard design** (Ventes / Services / RH)  
- Apply **business storytelling across departments**

---

## 📊 Dashboard Breakdown

### 🔹 Key Metrics (KPIs)
- **Total Sales Reps**: 48  
- **Top City (Sales Reps)**: Rabat (16)  
- **Avg. Age of Sales Reps**: ~35 years  
- **Avg. Base Salary**: €5,100–€5,500  
- **Top Service by Revenue**: Box IP-TV (€3.02M)  
- **Highest Abandonment**: Box Cloud-Life (10 To) → 5,950 abandonments/year  
- **Lowest Abandonment**: Box IP-TV-VIP → 950/year  

→ Indicates **premium tiers reduce churn**, while entry-level plans face high attrition.

---

### 🔹 Ventes (Sales) Tab
#### 📈 CA par ville et Service
- Bar chart showing revenue per city & service:
  - **Rabat**: highest revenue (~2M+)
  - **Marakech**, **Casablanca**, **Tanger**: lower but balanced
- Reveals **Rabat as commercial hub**.

#### 💰 Somme de CA par Service
- Stacked bar:  
  - **Box IP-TV**: €3.02M (57.2% of total)  
  - **Box Soft**: €2.49M  
  - **Box Cloud**: €1.73M  
→ Confirms **IP-TV is the core revenue driver**.

#### 📉 Nombre d’abonnements par service/type
- Scatter plot showing subscription count vs. revenue by service tier:
  - High-volume, low-revenue: *Box Cloud-Life (10 To)*  
  - Low-volume, high-revenue: *Box IP-TV-VIP*, *Box Soft-VIP*  
→ Classic **volume vs. premium trade-off**.

#### 👥 Top Customers by Abandonments
- Table:  
  - **KOUTOS Youssef**: 221 abandonments  
  - **ZRAGUI Fatima**: 144  
  - **[Other]**: 122  
→ Opportunity for retention analysis or personalized outreach.

---

### 🔹 Services Tab
#### 📋 Service-Type Pricing Table
| Service-Type | Prix d’achat (abonnement/an) | Prix vente (abonnement/an) |
|--------------|-------------------------------|----------------------------|
| Box Cloud-Life (10 To) | 2,000 | 3,900 |
| Box Cloud-Premium (50 To) | 2,300 | 3,400 |
| Box IP-TV-Premium | 2,100 | 3,000 |
| Box Soft-VIP (30 Soft) | 5,950 | 7,000 |
→ Shows **healthy margins** (e.g., +95% on Box Cloud-Life).

#### 📉 Moyenne de Bénéfice par Service-Type
- Line chart showing profit trend across service types  
- Peaks at **Box IP-TV-Premium** and **Box Soft-VIP**  
→ Premium tiers deliver highest unit economics.

#### 🧮 Nombre de Service-Type par Service et Matricule Commercial
- Stacked bar chart:  
  - Each sales rep (matricule: A001, A002, etc.) assigned to cities/services  
  - **Box**: most reps assigned  
  - **Box IP-TV**: fewer reps, higher revenue per rep  
→ Suggests **efficiency opportunity**: optimize rep allocation.

---

### 🔹 RH (Human Resources) Tab
#### 👥 Nombre commerciaux par Ville
- Bar chart:  
  - Rabat: 16  
  - Marakech: 12  
  - Casablanca: 10  
  - Tanger: 10  
→ Aligns with revenue distribution.

#### 👩‍💼 Sexe & Ville (Sankey-like Flow)
- Visual shows:  
  - Total reps: 48  
  - Female (F): 28  
  - Male (M): 20  
  - Breakdown by city (e.g., Rabat: 9 F / 7 M)  
→ Highlights **gender balance** (58% female), unusual in sales roles — strong diversity.

#### 📅 Age Moyen par Ville
- Line chart:  
  - Casablanca: ~39 yrs  
  - Rabat: ~36 yrs  
  - Marakech: ~35 yrs  
  - Tanger: ~30 yrs  
→ Younger teams in Tanger → potential for growth & training.

#### 💰 Moyenne de Salaire de base (euro) par Ville
- Donut chart:  
  - Rabat: €5,500 (26.83%)  
  - Marakech: €5,400 (26.34%)  
  - Casablanca: €5,100 (21.95%)  
  - Tanger: €5,100 (24.88%)  
→ Higher salaries in capital (Rabat), justified by performance.

#### 🗺️ Carte géographique (Tanger focus)
- Map of Morocco highlighting key cities  
- Blue pins on Rabat, Casablanca, Marakech, Tanger  
- Supports regional decision-making.

---

## 📐 Methodology
- Data modeling: Star schema (`Sales`, `Services`, `HR`, `Cities` tables)  
- DAX measures include:
  - `Total Revenue`, `Avg Salary`, `Abandonment Rate`, `Profit per Service`
  - `% of Total`, `Rank by City`, `Gender Ratio`
- Use of:
  - Multi-tab navigation (Ventes / Services / RH)
  - Sankey-style flow (Sexe → Ville)
  - Conditional formatting (color-coded bars/charts)
  - Interactive slicers (Ville, Service-Type)
- Visual design: Corporate blue/orange theme with clean layout

---

## 🛠️ Tools & Technologies
- **Power BI Desktop**  
- **Intermediate DAX** (CALCULATE, DIVIDE, RELATED, SUMX, RANKX)  
- **Geospatial visualization** (Morocco map)  
- **Cross-functional dashboard design** (Sales + HR + Service)  
- **Dashboard layout & storytelling** (tab-based navigation for role-specific views)

---

## 📌 Key Insights
✅ **Rabat dominates in sales reps (16) and revenue (€2M+)** — strategic priority city  
✅ **Box IP-TV drives 57% of revenue** — core product; protect & expand  
✅ **Premium tiers (VIP, Premium) have lowest abandonment** — invest in upselling  
✅ **High abandonment in entry-tier services** (e.g., Box Cloud-Life) — review onboarding/pricing  
✅ **Sales team is 58% female** — strong diversity advantage  
✅ **Tanger has youngest team (avg 30 yrs)** — high potential for development  
✅ **Salary correlates with city importance**, not just tenure — market-aligned pay  

---

## 📁 Repository Structure
├── Sales_Management_HR_PB19.pbix
├── Dataset/
│ ├── sales_data.csv
│ ├── services_catalog.csv
│ ├── hr_employees.csv
│ └── cities_geo.csv
├── Screenshots/
│ └── sales_hr_pb19.png
└── README.md


---

## 🚀 Project Purpose
This project was built as a **portfolio Power BI project** to:  
- Practice **cross-functional analytics** (Sales + HR + Service)  
- Improve **dashboard architecture with multi-tab navigation**  
- Apply **geographic, demographic, and financial segmentation**  
- Simulate **analytics reporting for telecom or SaaS companies**

---

## 📬 Contact
**Mustapha Tarfi**  
📍 Morocco  
🔗 LinkedIn: [https://www.linkedin.com/in/mustapha-tarfi-1106b5283/](https://www.linkedin.com/in/mustapha-tarfi-1106b5283/)  

