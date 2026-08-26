# Global Disaster Analysis Dashboard | Tableau

An interactive **Tableau dashboard analyzing historical disaster events and their human and economic impact**. It brings event frequency, deaths, affected populations, reported damage, disaster types, and geographic patterns into one analytical view.

## Why this project matters

Disaster datasets can reveal very different stories depending on whether you look at **frequency, human impact, or economic damage**. This dashboard makes those dimensions easier to compare so users can identify where disasters occur often, where their consequences are greatest, and how patterns vary by country and disaster type.

## Live dashboard

**[View the interactive dashboard on Tableau Public](https://public.tableau.com/app/profile/bhaskar.nakka4980/viz/DisasterAnalysis_17869126013330/Globaldashboard)**

![Global Disaster Analysis Dashboard](images/Disaster%20Analysis%20Dashboard.png)

## Key metrics

| Metric | Value |
|---|---:|
| Total disaster events | **15,090** |
| People affected | **8.542B** |
| Total deaths | **23M** |
| Total reported damage | **6.698B** |
| Average deaths per event | **1,519** |
| Average damage per event | **444M** |

> **Data note:** These are aggregate figures from the supplied dataset. They are not current global disaster totals, and reported monetary and impact values depend on the source data's definitions, coverage, and completeness.

## What the dashboard analyzes

- Disaster events and frequency over time
- Deaths and affected populations
- Reported economic damage
- Disaster types and severity
- Country-level impact
- Geographic distribution of disaster activity
- Differences between event frequency and overall impact

## Business questions

- How has disaster activity changed over time?
- Which disaster types occur most frequently?
- Which countries show the greatest human impact?
- Where are reported economic losses highest?
- Which disaster types combine high frequency with high severity?
- How does impact vary across countries and hazard types?

## Dashboard views

### Overview

High-level KPIs summarizing events, deaths, affected population, and reported economic damage.

### Time Analysis

Tracks disaster activity and impact across years to identify trends and unusually active periods.

### Geographic Analysis

Compares disaster activity and impact across countries.

### Disaster-Type Analysis

Breaks events down by hazard type to compare frequency and impact.

### Human & Economic Impact

Separates human consequences from reported economic losses to support a clearer comparison of disaster impact.

## Dataset

The project uses a historical disaster dataset based on **EM-DAT International Disaster Database** country-profile data.

The repository includes:

- `data/disaster-events.csv` — source dataset
- `tableau/Disaster Analysis.twbx` — Tableau workbook

The analysis depends on the definitions, coverage, and completeness of the supplied source data.

## Tools

- **Tableau** — dashboard development and visual analysis
- **CSV** — source data
- **Git / GitHub** — version control and documentation

## Skills demonstrated

- Data analysis
- Geographic analysis
- Trend analysis
- Comparative analysis
- KPI design
- Interactive dashboard design
- Business intelligence
- Data storytelling

## Repository structure

```text
disaster-dashboard/
├── data/
│   └── disaster-events.csv
├── images/
│   └── Disaster Analysis Dashboard.png
├── tableau/
│   └── Disaster Analysis.twbx
└── README.md
```

## Scope

This is a portfolio analysis of historical disaster records. It demonstrates analytical and dashboarding skills; it is **not** a live disaster-monitoring, prediction, or forecasting system.

## Author

**Bhaskar Nakka** — Data Analyst | SQL · Python · Tableau · Power BI

For opportunities or project discussions: **[bn7740401@gmail.com](mailto:bn7740401@gmail.com)**
