# Power BI deliverables

## Files

- `internship-lifecycle-analytics.pbix` — final three-page interactive report and imported semantic model.
- `themes/sannan-power-bi-portfolio-theme.json` — reusable final theme with the report palette, typography, page background, borders, padding, and visual defaults.

## Report pages

1. **Overview** — enrollment, participation, score, click, and outcome KPIs.
2. **Engagement & Outcomes** — click and assessment intensity by final result, including a seven-day activity trend.
3. **Cohort Analysis** — first-30-day activity and continued engagement for the early-active cohort.

The model also contains a hidden `Outcome ToolTip` page used by report visuals.

## Requirements

- Power BI Desktop on Windows to open or edit the PBIX.
- A compatible PostgreSQL analytical model and local connection settings to refresh the imported data.

No database password or environment-specific credential is stored in this repository. Power BI may prompt for credentials when a refresh is requested on another machine.
