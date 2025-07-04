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

### Bivariate 
- Population vs. Area: The correlation is weak (around 0.45). Having a large land area does not necessarily mean a country has a large population.
- Population vs. Density: There is no strong pattern here. Many small countries can be extremely crowded while large ones can be sparsely populated.
- Population vs. Growth Rate: The correlation is close to zero. Some large countries are still growing quickly, while others have stable or even declining populations.
- Density vs. Growth Rate: Countries with high population density can still experience rapid growth, which may increase pressure on resources and infrastructure.
- Area vs. Density: There is a slight negative trend. Larger countries tend to have lower population density on average.







