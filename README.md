

# QSS 45 Final Project

## Commute Inequality in the Bronx and Manhattan

**Author:** Balla Sy  
**Course:** QSS 45 — AI and Machine Learning for Social Science
## Website: https://ballasy27-spec.github.io/qss45-final/

## Project Overview

This project examines differences in commuting burden between census tracts in the Bronx and Manhattan using 2015 American Community Survey 5-year data.

The main research question is:

**Do Bronx census tracts experience longer average commute times than Manhattan census tracts, and how much of this difference is associated with public-transit use and socioeconomic characteristics?**

The analysis uses 602 census tracts after cleaning:
- 327 Bronx tracts
- 275 Manhattan tracts

## Data

Data are pulled from the U.S. Census Bureau API using the 2015 ACS 5-year Data Profile.

Variables include:

- Mean commute time
- Public-transit use
- Median household income
- Poverty rate
- Unemployment rate
- Work-at-home rate
- Borough

## Repository Structure

```text
code/
    00_data.ipynb
    01_models.ipynb
    02_final_figures.ipynb

data/
    qss45_bronx_manhattan_clean.csv

output/
    figures and regression tables
