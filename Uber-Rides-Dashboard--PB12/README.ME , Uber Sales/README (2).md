# 🚖 Uber Rides Performance Dashboard — Power BI

## 📌 Project Overview  
This project analyzes **Uber ride data** using **Power BI**, with the objective of understanding **booking trends, revenue distribution, customer behavior, driver performance, and geographic demand patterns**.  

The dashboard is designed to showcase **data visualization, exploratory analysis, and business storytelling skills**, using real-world ride-hailing platform data — perfect for demonstrating operational insight in the mobility and gig economy sector.

---

## 👀 Dashboard Preview  
<img width="383" height="213" alt="Uber-Rides-Dashboard---PB12 screenshots" src="https://github.com/user-attachments/assets/e2222f33-f217-4b3c-971a-c7b457999d87" />

*(Screenshot captured January 12, 2026)*

---

## 🎯 Objectives  
- Analyze **total bookings, total value, and average booking value**  
- Compare **bookings by vehicle type, pickup location, and day of week**  
- Understand **revenue distribution by pickup zone**  
- Visualize **booking trends over time (by hour and date)**  
- Explore **distance vs value correlation** and **driver ratings impact**  
- Practice **dashboard design and analytical storytelling** in Power BI

---

## 📊 Dashboard Breakdown

### 🔹 Key Metrics (KPIs)
- **Total Bookings**: 148.77K  
- **Total Value**: $52M  
- **Avg. Booking Value**: $508.30  
- **Ride Distance**: 150K (units likely km or miles)  
- **Filters**: Pickup Location, Date

---

### 🔹 Vehicle Type by Booking ID  
- Area chart showing decline in bookings by vehicle type:  
  - Auto → Go Mini → Go Sedan → Bike → Premium Sedan → eBike → Uber XL  
→ Reveals **Auto as most booked**, with sharp drop-off for premium/electric options

---

### 🔹 Total Revenue by Pickup Location  
- Horizontal bar chart showing top zones:  
  - Barakhamba Road: **$0.34M**  
  - Khandsa: **$0.34M**  
  - Subhash Chowk: **$0.33M**  
  - Patnauli Chowk: **$0.31M**  
  - Badarpur: **$0.33M**  
→ Highlights **high-demand pickup zones** — key for driver allocation and surge pricing

---

### 🔹 Booking Value by Date  
- Histogram showing distribution of booking values  
- Peak around **$0–$500**, long tail up to **$4000**  
→ Indicates **majority of rides are mid-range**, with occasional high-value trips

---

### 🔹 Total Bookings by Day  
- Bar chart showing bookings per day of week:  
  - Monday to Sunday all relatively balanced  
→ Suggests **consistent demand throughout the week**, no strong weekend peak

---

### 🔹 Nombre de Booking ID par Time  
- Line chart showing hourly booking volume:  
  - Peaks around **08:00, 12:00, 18:00**  
  - Low activity between **02:00–05:00**  
→ Confirms **commute & mealtime spikes**, useful for dynamic pricing and driver incentives

---

### 🔹 Booking by Customers  
- Bar chart showing customer segments (likely anonymized IDs):  
  - Customer 1 to 10 — all around **0.5M to 1.0M bookings each**  
→ Suggests **no single dominant customer**, but consistent repeat usage across base

---

### 🔹 Distance vs Value  
- Scatter plot showing relationship between **ride distance and fare**  
- Strong positive correlation → longer rides = higher value  
- Some outliers show **short rides with high value** (possibly surge pricing or premium service)

---

### 🔹 Booking Value by Driver Ratings  
- Bar chart showing average booking value by driver rating (4.1–4.7):  
  - 4.7: **$7.0M**  
  - 4.6: **$4.6M**  
  - 4.5: **$3.6M**  
  - 4.4: **$3.5M**  
  - 4.3: **$2.4M**  
  - 4.2: **$2.4M**  
  - 4.1: **$2.4M**  
→ Reveals **higher-rated drivers generate more revenue** — suggests quality drives loyalty & spending

---

## 📐 Methodology
- Data cleaning and preprocessing (handling missing values, standardizing locations/ratings)  
- Creation of calculated measures:  
  - `Avg Booking Value = DIVIDE([Total Value], [Total Bookings])`  
  - `Revenue by Zone = SUMX(FILTER(Bookings, Bookings[PickupLocation] = "Barakhamba Road"), Bookings[Value])`  
- Time-based aggregation (hourly/daily trends)  
- Use of:  
  - KPI cards  
  - Bar charts  
  - Area charts  
  - Scatter plots  
  - Histograms  
  - Filters (Pickup Location, Date)  
- Focus on **visual consistency, readability, and dark theme with white/blue accents**

---

## 🛠️ Tools & Technologies
- **Power BI Desktop**  
- **Data modeling** (star schema implied)  
- **Basic–Intermediate DAX** (aggregations, ratios, time intelligence)  
- **Data visualization principles** (color theory, spacing, hierarchy)  
- **Dashboard layout & storytelling** (flow from overview → deep dive)

---

## 📌 Key Insights
✅ **148.77K bookings generating $52M revenue** — healthy scale and monetization  
✅ **Auto is the most booked vehicle type**, while premium/electric options lag  
✅ **Barakhamba Road and Khandsa are top revenue zones** — prioritize driver supply here  
✅ **Booking value peaks around $0–$500**, with rare high-value outliers  
✅ **Demand peaks at 08:00, 12:00, 18:00** — align with commute & meal times  
✅ **Higher-rated drivers generate more revenue** — quality drives customer spend  
✅ **Distance strongly correlates with fare** — supports transparent pricing models  
✅ **No strong weekday bias** — consistent demand across days

---

## 📁 Repository Structure

├── Uber_Rides_Dashboard.pbix
├── Dataset/
│ └── uber_rides_data.csv
├── Screenshots/
│ └── uber_rides_dashboard.png
└── README.md


---

## 🚀 Project Purpose
This project was built as a **portfolio Power BI project** to:  
- Practice **mobility and gig economy analytics**  
- Improve **dashboard design and visual storytelling**  
- Apply **business-oriented insight generation**  
- Simulate **analytics reporting for ride-hailing platforms like Uber or Lyft**

---

## 📬 Contact
**Mustapha Tarfi**  
📍 Morocco  
🔗 LinkedIn: [https://www.linkedin.com/in/mustapha-tarfi-1106b5283/](https://www.linkedin.com/in/mustapha-tarfi-1106b5283/)  
