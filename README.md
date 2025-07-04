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

## Key Insights & Deep Dive
- 50%+ of the world’s population is in Asia.
  * add charts
- Top 5 countries contribute nearly 50% of the total population.
- Bangladesh shows high density (>1,200 people/km²) despite small area.
- Russia is the largest by land area but has a relatively low density (~8 people/km²).
- Africa’s average population grew ~3× from ~300M (1970) to ~1B+ (2022).
- Some small countries have >2% annual growth, a potential demographic pressure.
- Europe’s population growth has nearly plateaued.

### Business Relevance
These trends shape resource demand, urban planning, and policy:
- High-density, high-growth areas may face housing, food, or infrastructure strain.
  * Add charts
- Large, sparsely populated areas may need different strategies for development and connectivity.
 * ASdd chartr

## Narrative
Over the last 50 years, the world’s population has more than doubled. Asia and Africa lead this growth, shifting the center of global population eastward and southward. Europe and the Americas have seen slower growth, with some countries nearing demographic stagnation. As the population landscape changes, planners and policymakers must balance urban crowding with sustainable development





