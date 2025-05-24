# Global Air Quality and Environmental Factors Analysis

## Overview
This project analyzes the relationships between air quality (measured by AQI), greenhouse gas (GHG) emissions, forest cover, and population density across countries worldwide. Using statistical and visual analysis, we explore how these environmental and demographic factors interact and differ across continents.

## Data
- **Source:** The analysis uses a dataset (`FinalAirData.csv`) containing country-level data on:
  - Air Quality Index (AQI) values
  - GHG emissions
  - Forest cover percentage
  - Population density
  - Continent and country codes
- **Rows:** 110 countries
- **Columns:** 8 (Country, Status, AQI Value, Code, GHG_Emissions, Forest cover, population_density, Continent)

## Research Questions & Hypotheses
1. **Does increased GHG emission correlate with higher AQI values?**
   - *Finding:* Statistically significant positive correlation.
2. **Does increased forest cover correlate with lower AQI values?**
   - *Finding:* No significant correlation found.
3. **Does increased population density correlate with higher AQI values?**
   - *Finding:* No significant correlation found.
4. **Do mean AQI values differ significantly across continents?**
   - *Finding:* Statistically significant differences found, especially between Europe and Asia.

## Methods
- **Statistical Analysis:**
  - Pearson correlation for continuous variables
  - ANOVA and Tukey's HSD for group differences
- **Visualization:**
  - Choropleth world maps for AQI, GHG emissions, forest cover, and population density
  - Scatter plots for AQI vs. GHG emissions, forest cover, and population density
  - Box plots for AQI across continents
- **Tools:** Python, pandas, plotly, scipy, statsmodels

## Key Findings
- **GHG emissions and AQI:** Higher GHG emissions are associated with higher AQI values (worse air quality).
- **Forest cover and AQI:** No significant relationship found.
- **Population density and AQI:** No significant relationship found.
- **Continental differences:** AQI values differ significantly between continents, notably between Europe and Asia.

## How to Run
1. Place `FinalAirData.csv` in the same directory as `Notebook.ipynb`.
2. Open and run `Notebook.ipynb` in Jupyter or Google Colab.

## Dependencies
- pandas
- plotly
- scipy
- statsmodels

## Authors
- Youssef Ihab
- Ahmed Yasser
- Youssef Ashoush
- Youssuf Wael