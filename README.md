# Global Disaster Analysis Dashboard | Tableau

An interactive **Tableau dashboard analyzing historical natural-disaster records across time, geography, disaster type, human impact, and reported economic damage**. The project turns a large event-level dataset into a visual analysis of where disasters occur, how their impacts differ, and how patterns change over time.

## Live dashboard

**[View the interactive dashboard on Tableau Public](https://public.tableau.com/app/profile/bhaskar.nakka4980/viz/DisasterAnalysis_17869126013330/Globaldashboard)**

![Global Disaster Analysis Dashboard](images/Disaster%20Analysis%20Dashboard.png)

## Project objectives

The dashboard is designed to answer questions such as:

- How does reported disaster activity change over time?
- Which disaster types appear most frequently in the dataset?
- Which countries record the largest human impact?
- Where are reported economic losses highest?
- How do event frequency and impact differ across disaster types?
- Which countries and hazard categories show notable patterns?

## Dashboard analysis

### Executive Overview

Summarizes the main measures available in the dataset, including:

- Disaster events
- People affected
- Deaths
- Reported economic damage

### Time Analysis

Explores disaster activity and impact across years to identify long-term patterns and periods with higher recorded activity.

### Geographic Analysis

Compares disaster activity and impact across countries and geographic regions.

### Disaster-Type Analysis

Breaks records down by disaster type and subtype to compare frequency and recorded consequences.

### Human & Economic Impact

Examines deaths, affected populations, and reported damage as separate dimensions of disaster impact.

## Dataset

The repository uses a historical disaster dataset containing country-year records and disaster classifications.

Key fields include:

- Year
- Country
- ISO code
- Disaster group
- Disaster subgroup
- Disaster type
- Disaster subtype
- Total events
- Total affected
- Total deaths
- Total damage (USD, original)
- Total damage (USD, adjusted)
- CPI

The repository data extends through **2023**. The source file contains historical records rather than live disaster information.

> **Important data note:** Aggregate values in this project depend on the supplied dataset and its definitions, coverage, and completeness. Reported damage and impact figures should not be interpreted as current global totals.

## Tools & workflow

**Tableau** → dashboard development, calculated analysis, filtering, geographic views, and data storytelling

**CSV** → source dataset

**Git / GitHub** → version control and project documentation

## Skills demonstrated

- Data analysis
- Exploratory data analysis
- Time-series trend analysis
- Geographic analysis
- KPI design
- Comparative analysis
- Interactive dashboard development
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

## Scope & limitations

This is a **portfolio analytics project based on historical disaster records**. It demonstrates Tableau, data analysis, visualization, and storytelling skills.

It is **not** a live disaster-monitoring, early-warning, prediction, forecasting, or emergency-response system.

## Author

**Bhaskar Nakka** — Data Analyst | SQL · Python · Tableau · Power BI

For opportunities or project discussions: **[bn7740401@gmail.com](mailto:bn7740401@gmail.com)**
