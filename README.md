# World Population EDA Project

## Executive Summary
This project analyzes global population trends from 1970 to 2022 to understand how countries and continents have grown and shifted demographically. We examine population, area, density, and growth patterns to uncover meaningful insights for planners and policymakers.


## Entity-Relationship Diagram (ERD)
[Country] ---- (belongs to) ----> [Continent]

Country:
- Name
- Area (km²)
- Population (by year)
- Density
- Growth Rate
- World Population %

Continent:
- Name
- Aggregated metrics (mean, median, trends)
