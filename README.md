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


## Project Overview
Dataset: world_population.csv

Time Period: 1970–2022

Key Columns: Country, Continent, Population (multiple years), Area, Density, Growth Rate

Tools: Python (pandas, seaborn, matplotlib)

## Analysis Highlights

### Univariate
- Population, Area, Density, and Growth Rate distributions were plotted.
- The distribution of country populations is heavily right-skewed, with a small number of countries (e.g., China, India) accounting for a significant proportion of the total global population
- Density and Growth Rate vary widely.




