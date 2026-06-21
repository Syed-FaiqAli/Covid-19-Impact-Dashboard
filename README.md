# COVID-19 Impact Dashboard – Power BI Project

This repository showcases a comprehensive data analysis and visualization project built using Power BI and Microsoft Excel to analyze the impact of COVID-19 across India. The project encompasses interactive dashboards, a SWOT analysis framework, critical business questions, and a formal presentation—structured as a complete end-to-end data case study.

---

## Dashboard Structure

The `.pbix` Power BI file includes two specialized reporting views:

### 1. General Dashboard
* **Metrics:** Tracking of total and daily COVID-19 cases, mortality rates, and recovery figures.
* **Interactivity:** Dynamic filtering capabilities by state and historical date ranges.
* **Analysis:** High-level KPIs and cross-regional performance comparisons.

### 2. Management View
* **Strategic Insights:** Macro-level sector impacts and strategic operational takeaways.
* **Advanced Metrics:** Testing ratios, longitudinal trends, and granular drill-downs optimized for decision-makers.

---

## Dataset and Analysis Files

All foundational data and analytical frameworks are located within the `/data/` directory:

| File Name | Description |
| :--- | :--- |
| `covid_dataset.xlsx` | Raw region-wise daily COVID-19 statistical dataset utilized for dashboard ingestion. |
| `swot_analysis.xlsx` | Strategic SWOT analysis evaluating the nationwide pandemic response. |
| `key_gaps_questions.xlsx` | Documentation of identified operational gaps and core business questions addressed by the visual reports. |

> **Note:** The auxiliary Excel models served as the structural foundation for the data logic, semantic modeling, and analytical storytelling.

---

## Project Presentation

A formal executive-level PowerPoint presentation detailing the project life cycle is available in the `/presentation/` directory.

* **File:** `covid_dashboard_presentation.pptx`
* **Core Content:** Project scope, methodology, key analytical insights, dashboard walkthrough, and strategic conclusions.

---

## Dashboard Screenshots

### General Dashboard View
![General Dashboard Preview](screenshots/general-dashboard.png)

### Management Executive View
![Management Dashboard Preview](screenshots/management-dashboard.png)

---

## Technical Stack

* **Power BI:** Data modeling, DAX (Data Analysis Expressions), and Power Query ETL pipelines.
* **Microsoft Excel:** Data preprocessing, SWOT modeling, and gap analysis framework development.
* **Microsoft PowerPoint:** Executive presentation design.

---

## Repository Structure

```text
covid-dashboard-powerbi/
├── COVID_Dashboard.pbix
├── README.md
├── data/
│   ├── covid_dataset.xlsx
│   ├── swot_analysis.xlsx
│   └── key_gaps_questions.xlsx
├── presentation/
│   └── covid_dashboard_presentation.pptx
└── screenshots/
    ├── general-dashboard.png
    └── management-dashboard.png