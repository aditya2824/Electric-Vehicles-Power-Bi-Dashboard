# Electric-Vehicles-Power-Bi-Dashboard
# 🚗 Electric Vehicle (EV) Adoption – Power BI Dashboard

## 📊 Overview

This project presents an interactive Power BI dashboard that visualizes patterns in **Electric Vehicle (EV) adoption** across various dimensions such as make, model year, city, electric range, and utility coverage.  
The goal is to provide **data-driven insights** to support **EV infrastructure planning and policy-making** in regions like Washington State.

---

## 🎯 Objective

> To explore how electric utility coverage, geographic distribution, and vehicle manufacturing trends influence EV growth and support decision-making for future infrastructure and sustainable transport policies.

---

## 👥 Team Members

- **Aditya Lande** (Team Lead) – Overall Dataset Patterns  
- **Sahil Mohite** – EV Types and Manufacturer-wise Distribution  
- **Siddhesh More** – Policy Eligibility and Adoption Trends  
- **Harsh Khedekar** – Model-Level and Range Comparisons  
- **Omkar Sanap** – Geographic and Pricing Insights

---

## 📁 Dataset

- **Source:** [Washington State Department of Licensing – EV Population Data](https://data.wa.gov/)
- **Format:** CSV  
- **Fields Used:**
  - VIN (limited sample for analysis)
  - Make, Model, Model Year
  - Electric Range, Base MSRP
  - Electric Utility, City, County
  - Clean Alternative Fuel Vehicle (CAFV) Eligibility

---

## 📈 Visualizations Included

| Type               | Question Addressed                                  | Insight                                             |
|--------------------|------------------------------------------------------|-----------------------------------------------------|
| Bar Chart          | Top car makes by registration                        | Identifies leading EV manufacturers                 |
| Stacked Column     | EV type by top cities                                | Compare BEVs and PHEVs across locations             |
| Pie Chart          | CAFV eligibility                                     | Policy-driven EV adoption impact                    |
| Line Chart         | Registrations over model years                       | Growth trend in EV adoption                         |
| Treemap            | Model distribution within each make                  | Brand-model popularity                              |
| Column Chart (Avg) | Avg. electric range by make                          | Range performance comparison                        |
| Map Visualization  | EV density across counties                           | Regional EV distribution                            |
| Table              | Top 10 EV models by price                            | Premium EV market overview                          |
| Scatter Plot       | Model year vs electric range                         | Technological improvement over time                 |
| Donut Chart        | Vehicle count by electric utility                    | Utility-based service share                         |

---

## 📌 Tools Used

- **Power BI Desktop**
- **Microsoft Excel** (for initial data cleaning)
- **GitHub** (for version control and documentation)

---

## 🛠️ Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ev-adoption-dashboard.git
