# Global Disaster Analysis Dashboard | Tableau

An interactive **Tableau dashboard for analyzing global disaster events and their human and economic impact**. The project combines event frequency, deaths, affected populations, economic damage, geographic patterns, and disaster types into one analytical view.

## Live dashboard

**[View the interactive dashboard on Tableau Public](https://public.tableau.com/app/profile/bhaskar.nakka4980/viz/DisasterAnalysis_17869126013330/Globaldashboard)**

## Dashboard preview

![Global Disaster Analysis Dashboard](images/Disaster%20Analysis%20Dashboard.png)

## What this project analyzes

- Disaster events and frequency over time
- Deaths and people affected
- Economic damage
- Disaster types and severity
- Country-level impact
- Geographic distribution of disaster activity
- The relationship between event frequency and impact

## Key metrics

The dashboard currently reports these aggregate metrics for the included dataset:

| Metric | Value |
|---|---:|
| Total disaster events | **15,090** |
| People affected | **8.542B** |
| Total deaths | **23M** |
| Total reported damage | **6.698B** |
| Average deaths per event | **1,519** |
| Average damage per event | **444M** |

> **Data note:** These figures are dashboard aggregates from the supplied dataset. They should not be interpreted as current global disaster totals, and monetary/impact values depend on the source dataset's definitions and coverage.

## Business questions

The dashboard helps investigate:

- How has disaster activity changed over time?
- Which disaster types occur most frequently?
- Which countries experience the greatest human impact?
- Where are reported economic losses highest?
- Which events combine high frequency with high severity?
- How does disaster impact vary across countries and disaster types?

## Dashboard views

### Overview
Executive KPIs summarizing event count, deaths, affected population, and reported economic damage.

### Time analysis
Tracks disaster activity and impact across years to identify changes and unusually active periods.

### Geographic analysis
Compares disaster activity and impact across countries.

### Disaster-type analysis
Breaks events down by hazard type to compare frequency and impact.

### Human and economic impact
Separates the two major impact dimensions so users can compare where disasters have the greatest consequences for people and economies.

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
- Data visualization
- Geographic analysis
- Trend analysis
- KPI design
- Comparative analysis
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

This is a portfolio analysis of historical disaster records. It is intended to demonstrate analytical and dashboarding skills, not to provide a live disaster-monitoring or forecasting system.

## Author

**Bhaskar Nakka** — Data Analyst | SQL · Python · Tableau · Power BI

For opportunities or project discussions: **[bn7740401@gmail.com](mailto:bn7740401@gmail.com)**
