# ⚡ Electric Vehicle (EV) Adoption Analytics Dashboard – Power BI Project

## 📌 Project Overview

This project presents a comprehensive and interactive **Power BI Dashboard** that analyzes and visualizes the adoption trends of **Electric Vehicles (EVs)** using real-world data from Washington State.

The goal is to uncover critical insights into the growing EV market, enabling stakeholders such as government agencies, city planners, electric utility providers, and auto manufacturers to make **data-driven decisions** regarding **EV infrastructure development**, **policy planning**, and **sustainable transportation strategies**.

---

## 🎯 Key Objectives

- Identify **patterns in EV adoption** over time.
- Compare **EV make and model popularity**.
- Analyze **EV range improvements and pricing trends**.
- Visualize **regional concentration** of EVs across cities and counties.
- Examine **electric utility coverage** and **CAFV policy eligibility**.
- Support **future planning** for charging infrastructure and clean energy incentives.

---

## 📁 Dataset Details

- **Source:** [Washington State Department of Licensing – EV Registration](https://data.wa.gov/)
- **Format:** CSV
- **Total Records:** ~180,000+
- **Fields Used:**
  - `Make`, `Model`, `Model Year`
  - `Electric Vehicle Type` (BEV / PHEV)
  - `Electric Range` (in miles)
  - `Base MSRP` (Manufacturer’s Suggested Retail Price)
  - `City`, `County`, `Electric Utility`
  - `CAFV Eligibility` (Clean Alternative Fuel Vehicle)
  - `Vehicle Location` (Used for mapping)

---

## 📊 Dashboard Features & Visual Insights

| 📍 Feature | 📈 Description |
|-----------|----------------|
| **Make-wise EV Distribution** | A bar chart displaying which car brands (like Tesla, Nissan, Chevrolet) are most prevalent in EV registrations. |
| **City-wise EV Type Comparison** | A stacked column chart showing how BEVs and PHEVs are distributed across top cities. |
| **CAFV Eligibility Share** | A pie chart indicating the proportion of vehicles that qualify for Clean Fuel incentives. |
| **Model Year Trendline** | A line graph depicting how EV registrations have grown year-over-year. |
| **Treemap of Models** | A treemap visualizing the diversity and density of EV models under each make. |
| **Range Analysis by Make** | Average electric range for different car manufacturers. Helps understand battery performance over time. |
| **Map Visualization** | An interactive map showing EV registration density across Washington counties. |
| **Top 10 EVs by Price** | A detailed table listing high-end EV models based on Base MSRP. |
| **Scatter Plot – Range vs Year** | This visual shows how newer models typically offer better electric ranges, reflecting battery tech improvements. |
| **Electric Utility Donut** | Displays how EVs are distributed across different electric utility companies. |

---

## 🧠 Insights Derived

- **Tesla dominates** the EV market in Washington with consistent growth across years.
- Cities like **Seattle, Bellevue, and Redmond** show the highest adoption rates.
- The majority of registered EVs are **Battery Electric Vehicles (BEVs)**, not hybrids.
- **Policy eligibility** (CAFV) is strongly correlated with increased EV adoption.
- Electric vehicle **range has increased significantly** in recent years, especially among top brands.
- Certain counties have **limited EV penetration**, indicating areas for future infrastructure expansion.

---

## 🚀 Future Scope

- Incorporate **real-time APIs** for live EV registration updates.
- Layer in **charging station availability and coverage**.
- Predict **EV adoption growth** using forecasting techniques in Power BI or Python.
- Integrate **environmental impact metrics** (e.g., carbon savings, fuel cost savings).
- Expand project to **national-level datasets** for a more global view.

---

## 🧰 Tools & Technologies

- **Power BI Desktop** – For interactive data visualizations and DAX-based KPIs.
- **Microsoft Excel** – Initial data cleaning and formatting.
- **GitHub** – Version control and collaboration.
- **Data Source:** Open Government Data from [data.wa.gov](https://data.wa.gov)

---

## 🛠️ How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/ev-adoption-dashboard.git
