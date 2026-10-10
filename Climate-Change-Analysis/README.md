# R-Statistics-Projects
# Climate Change Analysis: Greenhouse Gas Emissions

**Language:** R  
**Project Type:** Statistical Analysis and Data Visualization  
**Course:** PSTAT 100 — Introduction to Data Science, UC Santa Barbara  
**Team:** John Loren Chapman, Owen Chapman, Nico Chapman

## Project Overview

This project investigates the relationship between greenhouse gas (GHG) emissions and economic, demographic, and geographic factors across countries from 1990 to 2019.

Using publicly available datasets, we analyzed how GDP per capita, population, geographic region, and time relate to greenhouse gas emissions.

The project combines exploratory data analysis (EDA), statistical visualization, and multiple linear regression to identify patterns in global emissions.

## Research Question

**How are greenhouse gas emissions associated with GDP per capita, population, and geographic region across countries from 1990–2019?**

The analysis also examines how these relationships evolved over time.

## Technologies and Skills

- **R** — Data cleaning, transformation, statistical analysis, and modeling
- **tidyverse / dplyr** — Data manipulation and dataset merging
- **ggplot2** — Statistical visualizations
- **Multiple Linear Regression** — Modeling relationships between emissions and country-level variables
- **Exploratory Data Analysis** — Identifying distributions, trends, and relationships
- **Residual Analysis** — Evaluating model assumptions and performance

## Data Sources

The analysis integrates four publicly available datasets:

1. **Climate Watch:** Historical greenhouse gas emissions
2. **World Bank:** GDP per capita
3. **World Bank:** Country population
4. **Geographic region data:** Country-to-region classifications

The datasets were combined using country and year information to create a country-level panel dataset.

After cleaning and removing observations with missing values, the dataset contained **4,593 country-year observations**.

## Methodology

### 1. Data Preparation

- Imported datasets from multiple sources.
- Standardized country and year variables.
- Restructured datasets for analysis.
- Merged observations using country and year.
- Identified and removed missing observations.
- Applied logarithmic transformations to variables where appropriate.

### 2. Exploratory Data Analysis

Created visualizations to investigate patterns in greenhouse gas emissions:

- Histograms of emission distributions
- Line graphs of emissions over time
- Scatterplots comparing emissions with GDP per capita
- Scatterplots comparing emissions with population
- Boxplots comparing emissions across geographic regions

### 3. Multiple Linear Regression

Developed a multiple linear regression model to examine the associations between greenhouse gas emissions and several explanatory variables.

The primary model used:

- **Response:** Log greenhouse gas emissions
- **Predictors:** Log GDP per capita, log population, and year

Model diagnostics included comparisons of predicted versus observed emissions and residual analysis.

## Key Findings

**1. Greenhouse gas emissions increased over time.**

Average country-level emissions generally increased between 1990 and 2019.

**2. Population demonstrated a strong positive association with emissions.**

Countries with larger populations generally produced higher total greenhouse gas emissions.

**3. GDP per capita was positively associated with emissions.**

The regression analysis suggested that countries with higher GDP per capita tended to have higher emissions when controlling for population and year.

**4. Geographic differences were observed.**

The distribution of emissions varied across regions, highlighting differences between countries and geographic areas.

**5. Model limitations remained.**

Residual diagnostics suggested that some patterns and variation were not fully explained by the regression model.

These results describe statistical associations rather than establishing causal relationships.

## Limitations and Future Improvements

The analysis had several limitations:

- Approximately 20.67% of the merged observations were removed because of missing data.
- The model did not include all potential drivers of greenhouse gas emissions.
- Relationships may differ across countries and geographic regions.
- The regression model may not fully capture nonlinear trends.

Future improvements could include incorporating industrial activity, renewable energy consumption, environmental policies, and more advanced statistical models.

## Project Report

The complete analysis includes statistical figures, regression results, residual diagnostics, and an appendix containing R code.

See the accompanying **Climate Change Analysis** PDF report for the full methodology and discussion.

## Authors

**John Loren Chapman, Owen Chapman, and Nico Chapman**

Collaborative open-ended final project for PSTAT 100 at the University of California, Santa Barbara.

## Skills Demonstrated

`R` `Data Cleaning` `Exploratory Data Analysis` `Statistical Modeling` `Multiple Linear Regression` `Data Visualization` `Data Interpretation`
