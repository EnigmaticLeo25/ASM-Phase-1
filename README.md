# **Applied Statisical Methods Assignment Phase-1**

# **Q1. IMDb Worst Rated Titles: Genre Impact Analysis**

## Project Overview

This project analyzes the IMDb Top 1000 Worst Rated Titles dataset to investigate whether movie genres significantly influence IMDb ratings. Using statistical methods such as one-way ANOVA, we uncover relationships between genres and ratings.

## Key Features

- Perform **One-Way ANOVA** to test the hypothesis that genres affect IMDb ratings.
- Generate an **ANOVA table** for detailed statistical results.
- Explore the impact of genres on IMDb ratings through statistical tests.

## Technologies Used

- **Python**: Core programming language for analysis.
- **Pandas**: For data cleaning and manipulation.
- **Scipy**: To perform one-way ANOVA.
- **Statsmodels**: For generating ANOVA tables.

## Dataset

- **Name**: IMDb Top 1000 Worst Rated Titles
- **Columns Used**:
  - `Genres`: To extract the primary genre.
  - `IMDb Rating`: For statistical testing and analysis.

## Conclusion

- The p-value from the ANOVA test is **0**, indicating a **statistically significant impact** of genres on IMDb ratings.
- The findings reveal that genres play a critical role in explaining variations in IMDb ratings.

# Q2. Chi-Square Test on Airline Passenger Satisfaction Dataset

## Overview

This project analyzes the relationship between **Passenger Satisfaction Levels** and **Travel Purpose** using the Chi-square test of independence. The dataset includes information about airline passenger satisfaction, and this analysis explores whether satisfaction levels are influenced by travel purposes (e.g., Business or Leisure).

## Features

- **Contingency Table**: Summarizes the observed counts of satisfaction levels for each travel purpose.
- **Chi-Square Test**: Tests the independence between satisfaction and travel purpose.

## Dataset

The analysis uses a dataset containing information about airline passenger satisfaction. Make sure the dataset file is in CSV format and includes the following columns:

- **Satisfaction**: The satisfaction level of passengers (e.g., Satisfied, Neutral, Dissatisfied).
- **TravelPurpose**: The purpose of travel (e.g., Business, Leisure).

## Requirements

Install the required Python libraries using the command below:

```bash
pip install -r requirements.txt
```
