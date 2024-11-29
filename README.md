# Analyzing Crime Trends and Hot Spots in Los Angeles

Click here to download the full project documentation as a PDF file: [LA Crime Analysis](https://github.com/user-attachments/files/17951779/LA_Crime_Analysis.pdf)
or access Tableau dashboard: [LA Crime Dashboard](https://public.tableau.com/app/profile/dominique.akinyemi/viz/LACrime_17315232169020/LACrimeOverview)

## Project Overview
This project explores crime data in Los Angeles (2020–2024), uncovering critical trends across time, geography, and demographics. By using SQL for data transformation and Tableau for visualization, the analysis provides actionable insights for law enforcement, policymakers, and the general public. The focus is on identifying patterns that can guide resource allocation, community engagement, and public safety strategies.

### Data Source
This analysis uses a data set, "[Crime Data from 2020 to Present](https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/2nrs-mtv8/about_data)," provided publicly by LA's Open Data portal and maintained by the LAPD.

---

## Skills Demonstrated
This project highlights a wide range of technical and analytical skills:

### Data Cleaning and Transformation
- Filtered and handled missing data for dates, times, crime codes, victim demographics, premise types, weapon usage, etc.
- Converted data types and handled error values/outliers. Pivoted wide and long data (split and joined columns).
- Cleaned and standardized complex string columns and descriptions.

### SQL Proficiency
- Created and managed databases and tables using MySQL Workbench and MySQL command line interface.
- Designed and executed complex queries to analyze temporal crime patterns, correlate crime types with victim demographics, and map geographic hotspots.
- Used `GROUP BY` and aggregate functions to reveal insights such as peak crime hours and common M.O. combinations.
- Employed calculated fields (e.g., `DATEDIFF` for reporting delays) and subqueries to handle advanced transformations and calculations.

### Data Visualization and Storytelling
- Built Tableau dashboards to visualize trends dynamically, enabling users to explore patterns interactively.
- Developed heatmaps for geographic insights, bar charts for victim demographics, line charts for trends, and histograms for numerical distributions.

### Analytical Thinking
- Identified high-impact insights such as the role of economic conditions in crime trends, prevalent crime types, and high-crime areas in Los Angeles.
- Synthesized findings into clear, actionable recommendations tailored to both public and government stakeholders.

---

## Key Insights

### Crime Trends
- **Yearly Patterns**: Crime peaked in **2022**, driven by a surge in vehicle theft and battery, before stabilizing in **2023**. Seasonal spikes align with summer months, particularly during **evening hours (6 PM–10 PM)**.  
- **Hourly Patterns**: More serious Part I crimes, such as theft and assault, are most frequent in the **evening**, while Part II crimes like fraud peak during **midday hours**.
- **Dominant Crime Types**: Vehicle, property, and **theft-related crimes** have dominated in recent years, indicating economic factors contributing to the rise in crime.

### Geographic Hot Spots
- **High-Crime Areas**: **Central LA**, **77th Street**, and other inner areas of LA report the most crimes, especially vehicle theft, robbery, and assault. These areas require targeted law enforcement and community programs.
- **Residential Crimes**: Burglaries and vandalism are prevalent in **Pacific** and **Southwest** neighborhoods, emphasizing the need for home security initiatives.

### Victim Demographics
- **Age Distribution**: Adults aged **26–40** are the most frequently reported victims, particularly in theft and assault cases.
- **Demographics**: **Hispanic** individuals are disproportionately affected across most crime types, reflecting Los Angeles’s demographic makeup, while **Black victims** are slightly overrepresented in younger age groups and **Black female victims** are overrepresented compared to males.

### Reporting Delays
- Most crimes are reported within **three days**, with **assault** cases often filed immediately. However, **fraud** and **identity theft** show longer delays, reflecting the time needed to recognize these incidents.

### Modus Operandi (M.O.)
- **Theft-related M.O.s** dominate, accounting for over **40%** of all incidents. Common tactics include stealth actions like “**Suspect removes item without detection**.”
- **Strong-arm methods**, such as physical force, are frequently reported in robbery and assault cases, particularly in public spaces like streets and sidewalks.

---

## Key Visuals
The visuals included in this repository provide snapshots of the analysis. To view the full analysis visualizations and dashboard, access Tableau Public here: [LA Crime Dashboard](https://public.tableau.com/app/profile/dominique.akinyemi/viz/LACrime_17315232169020/LACrimeOverview)

1. **Crime Trends Over Time**: The line charts display monthly and yearly crime trends for each of the top 10 crime types, distinguished by color.
![Top 10 Crime Trends](https://github.com/user-attachments/assets/dc80eb4f-af28-4065-927d-af75a615398d)

2. **Geographic Areas**: The map highlights high-crime areas like **Central LA** and **Hollywood**, while the stacked bar chart shows the breakdown of crime in each area.
![Filtered Area Map](https://github.com/user-attachments/assets/8cd00743-05ce-40be-9e4c-0b7e0d993742)
![Crime by Area](https://github.com/user-attachments/assets/0a340700-f526-44f2-b6ca-50adc6e2ceff)

4. **Victim Demographics** Bar charts showing the distribution of age, sex, and descent for reported victims.
![Descent v  Sex](https://github.com/user-attachments/assets/e686a4f3-2bd1-43ec-9df3-8f67356026b6)
![Victim Age](https://github.com/user-attachments/assets/27281a78-1bc6-4148-9076-56bcbcc7c48f)

---

## About the Author
This project was conducted as part of a portfolio to demonstrate my skills as a data analyst. It highlights my ability to clean, transform, and analyze large datasets while delivering actionable insights through professional visualizations and reporting. It also reflects my commitment to using data to drive meaningful change, uncovering insights that address real-world challenges. I aim to support stakeholders in making informed decisions for community safety and public welfare.

---

## Repository Contents
1. LA_Crime_v4.Rmd: The documentation in R Markdown format, with easy-to-copy SQL scripts to replicate this analysis.
2. [LA_Crime_Analysis.pdf](https://github.com/user-attachments/files/17951747/LA_Crime_Analysis.pdf): The final project report, containing detailed insights, visualizations, and recommendations in a visual format.

---
