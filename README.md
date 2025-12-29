# Toronto Neighbourhood Diversity & Socioeconomic Indicators Map
### Interactive Web Map (Leaflet + GeoJSON)

---

## Project Overview
This project is an interactive web map visualizing neighbourhood-level ethnic diversity and key socioeconomic indicators across the City of Toronto, based on 2021 census neighbourhood profile.  
It integrates census-based diversity metrics with crime rates, income levels, and labour force participation rate to explore spatial patterns and urban inequalities.

This map is designed for non-technical audiences, allowing users to intuitively explore complex spatial data through an interactive interface.

---

## Live Demo
👉 **View the interactive map here:**  
[website](https://sophiemaps.github.io/toronto-diversity-webmap/)

## Data Sources
- City of Toronto Open Data Portal
- Statistics Canada Census data  
- Neighbourhood boundary data (City of Toronto)

All datasets were cleaned, standardized, and joined at the neighbourhood level prior for visualization purpose.

---

## Methodology
1. Integrated neighbourhood boundary data with census and crime datasets
2. Calculated Shannon Diversity Index (SDI) to quantify ethnic diversity
3. Normalized and validated multiple socioeconomic indicators
4. Exported spatial data as GeoJSON
5. Built an interactive web map using Leaflet and JavaScript
6. Deployed the project using GitHub Pages

---

## Key Variables Visualized
- **Ethnic Diversity:** Shannon Diversity Index (SDI): higher SDI indicates higher ethnic diversity
- **Median Family Income**  
- **Renter Rate**  
- **Labour Force Participation Rate (LFPR)**  
- **Violent Crime Rate**  
- **Property Crime Rate**

Each neighbourhood is colour-coded by diversity level, with detailed indicators displayed on hover.

---

## 🛠 Tools & Technologies
- QGIS (data processing & spatial joins)  
- Leaflet.js (interactive web mapping)  
- HTML / CSS / JavaScript  
- GeoJSON  
- GitHub Pages (deployment)

---

## Notes
- Colour schemes of the map were selected to avoid judgement or bias when visualizing sensitive demographic data.
- This project focuses on exploratory spatial patterns and does not imply any causation.
