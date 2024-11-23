# **Applied Statisical Methods Assignment Phase-1**

# **Q1. IMDb Worst Rated Titles: Genre Impact Analysis**

## **Project Overview**

This project analyzes the IMDb Top 1000 Worst Rated Titles dataset to investigate whether movie genres significantly influence IMDb ratings. Using statistical methods such as one-way ANOVA, we uncover relationships between genres and ratings.

## **Key Features**

- Perform **One-Way ANOVA** to test the hypothesis that genres affect IMDb ratings.
- Generate an **ANOVA table** for detailed statistical results.
- Explore the impact of genres on IMDb ratings through statistical tests.

## **Technologies Used**

- **Python**: Core programming language for analysis.
- **Pandas**: For data cleaning and manipulation.
- **Scipy**: To perform one-way ANOVA.
- **Statsmodels**: For generating ANOVA tables.

## **Dataset**

- **Name**: IMDb Top 1000 Worst Rated Titles
- **Columns Used**:
  - `Genres`: To extract the primary genre.
  - `IMDb Rating`: For statistical testing and analysis.

## **Analysis Workflow**

1. **Data Cleaning**: Extract the primary genre and filter necessary columns.
2. **Statistical Test**: Perform a one-way ANOVA test to check for significant differences in IMDb ratings across genres.
3. **ANOVA Table**: Generate and interpret a detailed ANOVA table.

## **Conclusion**

- The p-value from the ANOVA test is **0**, indicating a **statistically significant impact** of genres on IMDb ratings.
- The findings reveal that genres play a critical role in explaining variations in IMDb ratings.
