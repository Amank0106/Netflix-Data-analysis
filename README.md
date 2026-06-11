# Netflix Data Analysis

An exploratory data analysis (EDA) project on the Netflix titles dataset using Python, Pandas, NumPy, Matplotlib, and Seaborn.

## Project Overview

This project explores Netflix's catalog to understand:
- the split between movies and TV shows,
- release year patterns,
- content added over time,
- country-wise production,
- rating distribution,
- top genres,
- most frequent directors and actors,
- and TV show season patterns.

## Dataset

The dataset contains information about Netflix titles such as:
- title
- type
- director
- cast
- country
- date_added
- release_year
- rating
- duration
- listed_in

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Cleaning Steps

- Handled missing values
- Converted `date_added` to datetime format
- Extracted season count from `duration`
- Cleaned multi-value columns like `listed_in` and `cast`
- Removed or replaced missing values where needed

## Exploratory Analysis Performed

- Movies vs TV Shows distribution
- Release year analysis
- Content added over time
- Country-wise releases
- Rating analysis
- Top 10 genres
- Directors with most titles
- Actors with most titles
- No. of seasons vs release year

## Key Insights

- Movies are more common than TV shows in the dataset.
- Netflix content saw strong growth in recent years.
- The United States leads in production, followed by India and the UK.
- Mature-rated content appears more frequently.
- Drama and related genres appear among the most common categories.
- Some directors and actors appear repeatedly across multiple titles.
- Most TV shows have a small number of seasons.

How to Run
Clone the repository.
Make sure the dataset file is in the same folder as the notebook.
Open NETFLIX_DATA_ANALYSIS.ipynb in Jupyter Notebook.
Run all cells to reproduce the analysis and plots.

Conclusion:
This project helped explore real-world data cleaning and visualization techniques while uncovering useful patterns in Netflix's catalog. It was a valuable step in improving my pandas, seaborn, and exploratory data analysis skills.

