# 📊 COVID-19 Global Data Exploration

Welcome to my portfolio project. This repository showcases a comprehensive end-to-end data analysis of global COVID-19 trends. Using **SQL Server** for heavy lifting and **Tableau** for storytelling, I transformed raw healthcare data into actionable visual insights.

---

## 📌 Project Overview
The goal of this project was to track and analyze the relationship between infection rates, death tolls, and vaccination rollouts across different geographic scales (Global, Continental, and National). 

*   **Data Source:** [Our World in Data](https://ourworldindata.org/covid-deaths)
*   **Live Dashboard:** [View on Tableau Public](https://public.tableau.com/app/profile/richieline.ramos/viz/COVIDDashboard_17743321768000/Dashboard1)

---

## 🛠️ Tools & Technologies
*   **Database:** SQL Server (T-SQL)
*   **Visualization:** Tableau Desktop / Public
*   **SQL Techniques:** CTEs, Window Functions (PARTITION BY), Joins, Data Casting, Views, Aggregate Functions

---

## 🏗️ Technical Workflow

### 1. Data Cleaning & Transformation
To ensure a "Single Source of Truth," I performed several critical transformation steps:
*   **Filtering:** Separated location-based data from aggregate continental data to prevent "double-counting" in global totals.
*   **Type Casting:** Converted data types (e.g., `nvarchar` to `float`) for mathematical consistency during rate calculations.
*   **Handling Nulls:** Managed null values in critical fields like `new_vaccinations` to maintain accurate rolling totals.

### 2. SQL Exploration Highlights
I utilized advanced SQL logic to uncover deep trends within the **85,000+ records**:
*   **Death Percentage:** Calculated the likelihood of mortality based on country-specific contraction rates.
*   **Rolling Analytics:** Implemented **Window Functions** to track cumulative vaccination progress over time.
*   **Optimized Architecture:** Used **CTEs** for multi-step calculations and created permanent **Views** to streamline the data pipeline for Tableau.

---

## 🖼️ Visual Insights
Below is a preview of the interactive dashboard. *Click the image to access the live, interactive version:*

[![COVID-19 Dashboard Preview](https://github.com/rishrishrish-png/PortfolioProjects/raw/main/dashboard_preview.png)](https://public.tableau.com/app/profile/richieline.ramos/viz/COVIDDashboard_17743321768000/Dashboard1)

**Key Dashboard Features:**
*   **Geographic Heat Map:** Visualizing the percentage of the population infected per country.
*   **Time-Series Analysis:** Comparing infection rates and vaccination rollouts per continent.
*   **Global Mortality Metrics:** Real-time percentage tracking of global deaths vs. cases.

---

## 🚀 How to Use This Repo
1.  **SQL Scripts:** Navigate to the `/Scripts` folder to view the `.sql` files containing the exploration logic and view creation.
2.  **Visuals:** Open the Tableau link provided above to interact with the final data product.

---

## 📬 Contact & Links
*   **LinkedIn:** [linkedin.com/in/richieliner](https://linkedin.com/in/richieliner)
*   **Tableau Profile:** [Richieline Ramos](https://public.tableau.com/app/profile/richieline.ramos)
*   **Email:** richieliner@gmail.com
