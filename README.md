# LA-Crime-Analysis
Visualization of Los Angeles crimes dataset using Python, Pandas, Matplotlib and Seaborn

## The Question
The LAPD wants to understand patterns in criminal activity across Los Angeles — by time, location, crime type, and victim demographics — to help allocate resources more effectively.

## The Data
- **Source:** Modified version of LA Open Data crime records
- **Fields:** Date/time reported and occurred, area, crime type, victim age/sex/descent, weapon used, location

## The Process
- Extracted the hour of occurrence from military time and aggregated crime counts by hour
- Counted crimes by patrol area to find the highest-volume locations
- Converted occurrence dates to weekday names and aggregated by day of week
- Calculated "reporting lag" (days between occurrence and report) and binned it into categories (same day, 1 day, 2–7 days, etc.)
- Identified the top 10 specific street locations by crime count
- Built a crosstab heatmap of the 10 most common crime types across all areas
- Filtered and visualized the distribution of victim ages
- Broke down victim demographics by gender and descent

## Key Insights
- **Peak crime hour:** 12:00 PM (noon) — the single highest-frequency hour
- **Highest-crime area:** Central division
- **Highest-crime day:** Friday, with 28,625 incidents — notably more than any other day
- **Average victim age:** 40 years old, with a concentration in the 25–35 range
- **Reporting lag:** a meaningful share of crimes are reported well after they occur, not same-day
- **Hotspot locations:** a small number of specific addresses (e.g. 600 S Broadway, 800 N Alameda St) account for disproportionately high crime counts — useful for targeted patrol planning

## Visuals
- Line chart: crimes by hour of day
- Bar chart: crimes by area
- Bar chart: crimes by day of week
- Bar chart: reporting lag categories
- Horizontal bar chart: top 10 crime locations
- Heatmap: crime type × area
- Histogram: victim age distribution
- Bar charts: victim gender and descent breakdown

## Tools
`Python` `Pandas` `Matplotlib` `Seaborn`
