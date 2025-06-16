# Climate Heat Trend Analysis

This project explores historical and projected surface temperature trends and extreme heat events from climate data between 2006 and 2080, focusing on an area near Manchester, UK. The objective is to identify seasonal temperature patterns, detect heat risk events, and analyze radiative, atmospheric, meteorological, and anthropogenic factors affecting temperature change.

## Project Scope
- Investigate long-term temperature trends (TREFHT, TREFMXAV_U)
- Identify moderate and extreme heat events (305K and 308K thresholds)
- Analyze influencing factors (e.g., radiation, humidity, wind, GHGs)
- Compare seasonal drivers and differences between extreme vs normal days

## Dataset
- Source: Simulated climate data (CESM-based)
- Period: 2006–2080 (27,374 entries)
- Location: Temperate oceanic region near Manchester
- Variables: Temperature, precipitation, solar radiation, wind, humidity, etc.

## Methodology
- Exploratory Data Analysis (EDA)
- Feature engineering (season, thresholds, normalization)
- Correlation analysis (Spearman)
- Seasonal and comparative analysis of influencing factors
- Visualization using Matplotlib and Seaborn

## 📁 Structure
project/
├── Project1_version2.ipynb # Main notebook with full analysis
├── ProjectReflection_Group1.ipynb # Reflection and learnings
├── environment.yml # Project environment dependencies
├── project_1.csv # Raw climate dataset
└── EEDS_Project1_Group1.pdf # Final presentation

## Results
- Detected year-over-year warming trend, with peak summer temperatures rising significantly.
- Identified days at risk for moderate (305K) and extreme heat (308K), highlighting public health concerns.
- Found distinct seasonal drivers (e.g., FSNS, QBOT, VBOT) affecting heat dynamics in summer vs. winter.

Course Info: https://zhonghuazheng.com/eeds

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/m-edal/Earth-Env-DS-MSc-Course/HEAD)
