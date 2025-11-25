Hospitals healthcare KPI dashboard

A recruiter-ready healthcare operations dashboard built with Power BI and Excel. It tracks patient flow, revenue, bed occupancy, lead times, clinical KPIs, and department performance with clean navigation and consistent logic.

---

## Highlights

- **Multi-page navigation:** Overview, Patient Flow, Financials, Bed Occupancy, Clinical KPIs, Department Performance
- **DAX rigor:** Time intelligence, dynamic measures, cohort comparisons, and clean filter handling
- **Design polish:** Consistent color palette, iconography, and responsive layout for executive review
- **Data integrity:** Transparent assumptions, data dictionary, and validation checks

---

## Screenshots

- **Overview:** images/overview.png  
- **Patient flow:** images/patient-flow.png  
- **Financials:** images/financials.png  
- **Bed occupancy:** images/bed-occupancy.png  
- **Clinical KPIs:** images/clinical-kpis.png

> Add 1200x630 social preview banner at images/social-preview.png

---

## Data and assumptions

- **Sources:** Synthetic hospital dataset modeled on typical operational tables (patients, admissions, discharges, billing, beds)
- **Privacy:** No personal data; files are anonymized or generated
- **Data dictionary:** docs/data-dictionary.md

---

## DAX catalog (selected)

- **Admissions per day**
- - **Bed occupancy rate**

- **Revenue (MTD/YTD)**

Full list in docs/dax-measures.md.

---

## File structure
---

## How to open and explore

1. **Power BI:** Open powerbi/papollo-hospitals.pbix
2. **Excel:** See excel/cleaning.xlsx for transformations
3. **Docs:** Read docs/metrics-definitions.md for KPI formulas and logic

---

## Use cases

- **Ops review:** Daily admissions, discharges, bed occupancy, and bottlenecks
- **Finance:** Revenue trends, payer mix, AR flags
- **Quality:** Clinical KPIs, lead times, outlier detection

---

## Roadmap

- **Short term:** Add departmental drilldowns and SLA heatmaps
- **Next:** Parameterized scenarios and data refresh pipeline sketch

---

## License

MIT — see LICENSE for details.
git init
git add .
git commit -m "Init: structure, README, license"
git branch -M main
git remote add origin https://github.com/USERNAME/papollo-hospitals-healthcare-dashboard.git
git push -u origin main


