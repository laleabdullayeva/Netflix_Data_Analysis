# Netflix_Data_Analysis
## Overview
This project is an Exploratory Data Analysis (EDA) of the Netflix Movies and TV Shows dataset. The goal of this project is to uncover trends, patterns, and insights regarding the content available on Netflix, such as content types, release years, ratings, and top producing countries.

## Tools & Libraries Used
* **Python** * **Pandas:** Data cleaning, manipulation, and aggregation.
* **Matplotlib:** Data visualization.

## Key Insights Discovered
* **Content Type:** Movies significantly outnumber TV Shows on the platform.
* **Top Ratings:** The most common content rating on Netflix is 'TV-MA', indicating a large volume of mature content.
* **Global Reach:** The United States is the top content-producing country, followed by India and the UK.
* **Growth Over Time:** There is a clear exponential growth in the number of titles released over the recent years, peaking around 2018-2019.

## Project Structure
* Data cleaning: Handling missing values in `director` and `rating` columns.
* Feature extraction: Converting the `duration` column into a purely numeric format for analysis.
* Visualizations: Pie charts, line plots, and histograms showing distribution of data.

## How to Run
1. Clone this repository.
2. Ensure you have Python and Jupyter Notebook installed.
3. Install required libraries: `pip install pandas matplotlib`
4. Download the `netflix_titles.csv` dataset and place it in the same directory.
5. Run the `Netflix_Data_Analysis.ipynb` notebook.
