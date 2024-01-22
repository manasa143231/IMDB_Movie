# IMDb Movies Dataset Analysis

## Overview

This project involves the analysis of an IMDb movies dataset, aiming to gain insights into the movie industry. The dataset contains information about various movies, including details such as release year, age rating, runtime, genre, IMDb rating, votes, and gross revenue.

## Steps Performed

### 1. Data Loading

- Loaded the IMDb movies dataset from the file "imdb_top_1000.csv".
- Displayed basic information about the dataset.

### 2. Data Cleaning

- Dropped unwanted columns including 'Poster_Link', 'Star1', 'Star2', 'Star3', 'Star4', and 'Meta_score'.
- Renamed columns for better readability.
- Handled missing values in the 'Gross' column.
- Consolidated different age ratings into three main categories: 'U' (Universal), 'UA' (Universal - Adult), and 'A' (Adult).
- Filtered out movies with missing or incorrect release years.

### 3. Data Transformation

- Converted 'Release Year' to integer type.
- Converted 'Runtime' to integer type.
- Cleaned and converted 'Gross Revenue' to numeric, adjusting for commas and scaling to millions.

### 4. Genre Analysis

- Grouped the data by genre and calculated the average IMDb rating for the top 10 genres.
- Created a horizontal bar chart to visualize the total counts of genres.

### 5. Movie Release Analysis

- Visualized the distribution of movie releases over different years using a histogram.

### 6. IMDb Rating Trends

- Created a line plot to visualize the relationship between 'Release Year' and 'IMDb Rating'.

### 7. Top Movies by Gross Revenue

- Identified and visualized the top 10 movies based on gross revenue using a bar chart.

## Data Visualization

- Utilized Matplotlib and Seaborn libraries for creating various visualizations.

## Conclusion

This analysis provides insights into the distribution of movie genres, trends in movie releases over the years, and the performance of top movies based on IMDb rating and gross revenue.

Feel free to explore the provided Python script for the detailed implementation of each step.
