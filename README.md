# Covid-19 Case Analysis from NYTimes dataset

This is our final project for Stat 184, where we will be demonstrating the skills we have learned in this course by analysing a datset which we have chosen to eb the Covid-19 dataset(https://github.com/nytimes/covid-19-data) provided by the new york times.

## Overview

This project provides a comprehensive analysis of COVID-19 cases and deaths across U.S. states using data from the New York Times. The analysis explores geographic patterns, temporal trends, and cumulative impacts of the pandemic from January 2020 to March 2023. Using R and the tidyverse framework, we apply data wrangling, visualization, and statistical techniques to uncover insights about how the virus spread across different states and over time. The project demonstrates skills in data cleaning, reproducible reporting, and ethical data practices following FAIR and CARE principles.
## Data Sources and Acknowledgements

**Primary Data Source:**
- New York Times COVID-19 Data: [https://github.com/nytimes/covid-19-data](https://github.com/nytimes/covid-19-data)
  - State-level dataset containing cumulative daily counts of COVID-19 cases and deaths
  - Data compiled from state and local health agencies
  - Coverage: January 21, 2020 to March 23, 2023

**Additional Resources:**
- R packages used: tidyverse, lubridate, janitor, knitr, kableExtra
- Project template provided by STAT 184 course materials
- Data follows FAIR (Findable, Accessible, Interoperable, Reusable) principles for open science
## Current Plan

The analysis is structured to answer key research questions about COVID-19 spread in the United States:

1. **Data Cleaning and Preparation**: Load and clean the NYTimes state-level dataset, calculating daily new cases and deaths from cumulative counts
2. **Geographic Analysis**: Compare total cases and deaths across states to identify regions most affected by the pandemic
3. **Temporal Trends**: Visualize cumulative case growth over time for selected states (Pennsylvania, New York, California) to identify surge periods
4. **Statistical Summaries**: Create tables showing top states by case counts and key metrics (first/last report dates)
5. **Reproducible Reporting**: Generate a professional PDF report using Quarto with proper documentation, citations, and visualizations

For detailed methodology and code documentation, see the `FP_QMD.qmd` file and `Project_Guidelines.md`.
## Repo Structure

```
3_FP_Naman_Riya_Aditi/
├── FP_QMD.qmd              # Main analysis file (Quarto document)
├── README.md               # Project overview and documentation
├── Project_Guidelines.md   # Course project requirements
├── us-states.csv           # NYTimes COVID-19 state-level data (local copy)
├── .gitignore              # Git ignore file
├── .lintr                  # R linting configuration
├── MLA9.csl                # MLA citation style
└── apa7.csl                # APA citation style
```

**Key Files:**
- **FP_QMD.qmd**: Contains all R code for data analysis, visualizations, and narrative text. This is the primary source file that generates the final report.
- **us-states.csv**: Local copy of the COVID-19 dataset for reproducibility (also loaded directly from NYTimes GitHub in the analysis)
- **README.md**: This file - provides project overview, data sources, and navigation guide

## Authors

**Team Members:**

- **Naman Khandelwal** ([@namanKhand](https://github.com/namanKhand))
  - Primary Code Reviewer and Contributor
  - Penn State University, STAT 184

- **Riya Merchant** ([@riyamerchant](https://github.com/riyamerchant))
  - Code Reviewer and Contributor
  - Penn State University, STAT 184

- **Aditi Kumar** ([@aditikumar2157](https://github.com/aditikumar2157))
  - Code Reviewer and Contributor
  - Penn State University, STAT 184

**Course:** STAT 184 - Introduction to R Programming (Fall 2025)

**Contact:** For questions about this project, please open an issue in this repository or contact the team members via GitHub. Also you can reach us at the emails: nmk5877@psu.edu(Naman), abk6167@psu.edu(Aditi), rvm6021@psu.edu(Riya)
