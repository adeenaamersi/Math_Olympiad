# Math Olympiad Analysis

## Project Overview

This project explores data from the International Mathematical Olympiad (IMO), a prestigious global championship for high school students in mathematics. Since its inception in 1959 in Romania, the IMO has expanded to include over 100 countries, becoming a platform for young mathematical talent worldwide. Each competition spans two consecutive days, featuring six challenging problems.

The primary goal of this project is to analyze historical data from the IMO to answer the following research questions:

1. How have country rankings shifted over time?

2. What is the distribution of participation by country and gender? What is the distribution of top scores?

## Inspiration

As a math major with a deep passion for mathematics, I chose this dataset for my first R project to combine my academic interests with real-world data analysis. My personal experience participating in math competitions like Kangaroo and district-level events inspired me to explore the trends and patterns in IMO data.

## Dataset Information

The analysis uses three datasets related to the IMO:

1. **Country Results (country_results)**: Contains information about the awards won by each country, including the number of gold, silver, bronze medals, and honorable mentions.

2. **Individual Results (individual_results)**: Details the scores of individual contestants.

3. **Timeline (timeline)**: Tracks participation trends by year, including the number of participating countries and gender distribution.

The data was sourced from the TidyTuesday repository.

## Approach

The analysis was conducted in R, and the following steps were taken:

1. Data Cleaning and Preparation:

    a. Removed the p7 column (irrelevant due to missing values).

    b. Excluded data prior to 1980 to ensure validity.
    
    c. Filtered out records with invalid scores or missing values in key columns.
    
    d. Reformatted the award column to categorize it into Gold Medal, Silver Medal, Bronze Medal, and Honorable Mention.
    
    e. Addressed missing gender data by excluding incomplete records for consistency.

2. Research Question Analysis:

    a. Country Rankings Over Time:

        i. Created a bar plot showing the number of gold medals won by each country in 2024.

        ii. Developed a line chart illustrating trends for the top four countries from 2000 to 2024, highlighting medal distributions.

    b. Participation by Country and Gender:

        i. Used a line chart to track the number of participating countries over the years.
        
        ii. Visualized gender distribution trends with a density plot.

    c. Distribution of Top Scores:

        i. Analyzed the distribution of gold medal scores using a violin chart.

## Visualizations

The project includes several visualizations to illustrate trends and patterns:

1. Bar plots and line charts for country rankings.

2. Density and line plots for participation trends.

3. Violin charts for score distributions.

## Results

1. Country Rankings: Identified trends in medal achievements and shifts in rankings over time.

2. Participation Trends: Observed an increase in gender diversity and overall country participation.

3. Top Scores: Analyzed patterns in high-performing scores, revealing consistent trends among top performers.

## Tools and Techniques

1. Programming Language: R

2. Libraries Used: ggplot2, tidyverse, patchwork

3. Analysis Techniques: Data cleaning, exploratory data analysis (EDA), and visualization

## Future Work

This project lays the foundation for deeper exploration into:

1. Regional or socio-economic factors influencing performance.

2. Correlations between contestant demographics and scores.

3. Temporal analysis of problem difficulty levels.

## Contact

If you have questions or suggestions, feel free to reach out:

Author: Adeena Amersi

Email: adeenaamersi@gmail.com
