# Exploratory Data Analysis (EDA) on Amazon Prime Video Dataset
## Project Overview
This project performs Exploratory Data Analysis (EDA) on the Amazon Prime Video dataset to uncover meaningful patterns, trends, and insights related to content production, distribution, and viewer targeting. The objective is to understand how content varies across countries, time, genres, ratings, and duration using systematic data cleaning and visualization techniques.
This analysis focuses on data-driven observations, not assumptions.

## Dataset Description
The dataset contains metadata about movies and TV shows available on Amazon Prime Video, including:

Title

Content type (Movie / TV Show)

Country

Release year

Genre

Age rating

Duration

Date added

During preprocessing, columns with poor analytical value due to excessive missing data were evaluated and handled appropriately.

## Data Cleaning & Preprocessing

The date_added column contained an extremely high number of null values, making it unreliable for temporal analysis.

Instead of forcing imputation or using weak assumptions, the column was removed to preserve data integrity.

Other columns were standardized and filtered to ensure consistency for analysis and visualization.

This decision was intentional and statistically justified.

## Key Insights & Findings
1. Country-wise Content Contribution

United States and India are the top contributors to Amazon Prime’s content library.

This highlights Amazon Prime’s strategic focus on major entertainment markets.

2. Content Type Distribution

Movies dominate the platform, accounting for approximately 80% of the total content.

TV Shows represent a significantly smaller share, indicating a movie-centric catalog.

3. Release Year Trend

A peak in content releases is observed in 2020.

This surge aligns with increased digital content consumption during the global pandemic period.

4. Genre Distribution

Drama and Comedy are the most prevalent genres.

This suggests a strong emphasis on high-engagement, mass-appeal content.

5. Age Rating Analysis

13+ and 16+ rated content appears in the highest volume.

This indicates a primary target audience of teenagers and young adults rather than children or strictly mature audiences.

6. Content Duration

Most movies fall within the 90–100 minute duration range.

This reflects industry-standard runtime preferences for mainstream films.

## Tools & Technologies Used

Python

Pandas & NumPy for data manipulation

Matplotlib & Seaborn for visualization

Jupyter Notebook for interactive analysis

## Conclusion

This EDA reveals that Amazon Prime Video prioritizes:

Movie-based content over TV shows

High-output regions like the US and India

Popular genres such as Drama and Comedy

Youth-focused age ratings

Standardized movie durations

The analysis demonstrates how structured data exploration can reveal platform-level content strategies without relying on speculation.

## Project Type

Academic Minor Project – Exploratory Data Analysis
