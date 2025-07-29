# Public Health Data Trend Analysis (COVID-19)

**Uncovering Pandemic Patterns for Informed Public Health Strategy**

---

## 📄 Project Overview

This project provides a comprehensive analysis of global COVID-19 trends, utilizing publicly available historical data. The primary objective was to identify key pandemic patterns, understand geographical and temporal disparities, and derive actionable insights to inform public health strategies.

Through this analysis, I demonstrate an end-to-end data pipeline, from raw data ingestion and transformation to robust data modeling and interactive visualization.

---

## 🎯 Problem & Motivation

The COVID-19 pandemic presented unprecedented global health challenges. Understanding its progression, identifying peak periods, and recognizing geographical variations are crucial for:
* Informing public health policy and resource allocation.
* Evaluating past interventions and their impact.
* Preparing for future health crises and potential disease waves.

This project aims to leverage data to contribute to that understanding.

---

## 📊 Key Findings

Based on the analysis, the following key insights were observed:

* **Significant Global Impact:** The pandemic resulted in over **676 million** confirmed cases and **6.8 million** deaths worldwide by early 2023, with cumulative figures showing a steady, non-decreasing trend.
* **Distinct Waves of Infection:** The global progression of the pandemic was characterized by clear waves, with notable spikes in monthly new confirmed cases in **January 2022** (coinciding with the Omicron variant) and significant death surges in **January 2021**.
* **Geographical Disparities:** **The United States** consistently recorded the highest cumulative confirmed cases globally. Furthermore, countries like **Peru** experienced a particularly high mortality rate of **5.8%**, highlighting severe localized impacts despite varying case numbers.
* **Comparative Trends:** Analysis of selected countries (e.g., Brazil, Argentina, Chile, Colombia) revealed diverse infection curves and mortality patterns, emphasizing varied regional responses and outcomes.

---

## 💡 Key Recommendations

Based on these findings, the following recommendations are suggested for public health stakeholders:

* **Proactive Pandemic Preparedness:** Implement continuous investment in and refinement of rapid response protocols for emerging health threats, especially concerning new variants, based on observed historical spikes.
* **Targeted Resource Allocation:** Strategically allocate resources (e.g., for testing, treatment, infrastructure) to disproportionately affected populations, such as regions with high case counts (e.g., the US) or elevated mortality rates (e.g., Peru).
* **Refine Crisis Management Protocols:** Develop robust epidemic management protocols and efficient patient flow management in medical facilities to mitigate the impact of future crises, informed by insights from past mortality surges.

---

## 🛠️ Tools & Technologies

* **Python:**
    * `Pandas`: Used for efficient data manipulation, cleaning, and essential transformation (specifically unpivoting the raw wide-format JHU data into a long, analytical format).
* **SQL (PostgreSQL):**
    * **PostgreSQL Database:** Utilized for robust data storage.
    * **PgAdmin:** Graphical interface for database management and executing SQL queries.
    * **SQL Queries:** Employed for data loading, advanced cleaning (e.g., handling inconsistent entries), feature engineering (e.g., calculating daily new cases/deaths using window functions like `LAG()`), and data aggregation.
* **Tableau Public:**
    * **Interactive Dashboard:** Designed and developed a dynamic dashboard for comprehensive data visualization.
    * **Custom Color Palettes:** Implemented a unique **Material Gruvbox** color scheme to enhance visual appeal and thematic consistency.

---

## 📁 Project Structure

The repository is organized as follows:

├── data/
│   ├── time_series_covid19_confirmed_global.csv  # Raw JHU confirmed cases data
│   ├── time_series_covid19_deaths_global.csv     # Raw JHU deaths data
│   └── covid_global_long_format.csv            # Cleaned, unpivoted data used for SQL import
├── notebooks/
│   └── data_pivot.ipynb                      # Jupyter Notebook for raw data unpivoting (Python/Pandas)
├── report/
│   └── Public Health Data Trend Analysis (COVID-19) Report.pdf # Full project report
└── README.md                                 # This file

---

## 🚀 Live Dashboard & Full Report

Explore the interactive dashboard and review the detailed project report:

* **[Click Here to View Live Tableau Dashboard](https://public.tableau.com/app/profile/marcelo.somma/viz/COVID-19DataTrendAnalysis/COVID-19Dashboard)**
* **[Click Here to Read the Full Project Report (PDF)](LINK_TO_PDF_IN_YOUR_GITHUB_REPO_HERE)**

---

## 📞 Contact

Feel free to connect with me for any questions or collaborations!

* **Marcelo Somma**
* **LinkedIn:** **[LinkedIn Profile](https://uy.linkedin.com/in/marcelo-somma/en?trk=people-guest_people_search-card)**

---
