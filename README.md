# Airline Arrival Delays Data Analysis

## Overview

This project analyzes arrival delays, cancellations, and diversions for four major airlines (ALASKA, AM WEST, UNITED, DELTA) across five major West Coast cities using a simulated dataset. The dataset was intentionally structured in a "wide" format with missing values, requiring cleaning, transformation, and analysis in R.

The project demonstrates:
- Reading and inspecting a complex, messy data file
- Handling missing values appropriately
- Tidying data from wide to long format using `tidyr`
- Summarizing and visualizing flight statuses using `dplyr` and `ggplot2`
- Comparing airline performance both overall and city-by-city
- Documenting the process with clear, reproducible R Markdown code

## Files

- `arrival_delays_expanded.csv`  
  The main dataset, in wide format, with multiple airlines, statuses, cities, and missing values.

- `Airline_Arrival_Delays_Expanded_Analysis.Rmd`  
  The R Markdown file containing all code, narrative, and output for the analysis. This file demonstrates best practices in data cleaning, transformation, and reporting.

## Instructions

1. **Clone or download the repository.**
2. **Open `Airline_Arrival_Delays_Expanded_Analysis.Rmd` in RStudio.**
3. **Ensure you have the necessary R packages:**
   - `dplyr`
   - `tidyr`
   - `readr`
   - `ggplot2`
   - `knitr`
4. **Knit the Rmd file to HTML to view the rendered analysis, or follow along in RStudio.**
5. **Review the code and narrative explanations in each section.**

## Key Learning Outcomes

- Practice transforming and tidying real-world style messy data.
- Understand the importance of handling missing values.
- Learn to compare airline performance with both aggregate and city-level summaries.
- Observe how overall vs. city-by-city analysis can produce different (sometimes contradictory) insights—a demonstration of Simpson’s Paradox.
- Gain experience producing reproducible, well-documented analysis in R Markdown.
