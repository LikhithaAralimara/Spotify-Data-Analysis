# Spotify-Data-Analysis
Spotify Data Analysis Project 

Welcome to the Spotify Data Analysis project! ,which provides a comprehensive exploration of Spotify music data, offering insights and visualizations on various aspects of music tracks.

## Overview

Spotify is one of the world's leading music streaming platforms, and its extensive music library provides a treasure trove of data for analysis. In this project, we dive into the Spotify dataset to uncover interesting patterns and trends related to music popularity, song attributes, and genre preferences.

## Getting Started

To get started with this analysis, follow these steps:

1. **Clone the Repository:**
   - Clone this repository to your local machine:

     ```bash
     git clone https://github.com/LikhithaAralimara/Spotify-Data-Analysis
     ```

2. **Download the Datasets:**
   - To perform the analysis in this Jupyter Notebook, you'll need to download the following datasets:
     - [tracks.csv](https://www.kaggle.com/datasets/lehaknarnauli/spotify-datasets?select=tracks.csv): This dataset contains information about various music tracks, which will be the primary data source for our analysis.
     - [SpotifyFeatures.csv](https://www.kaggle.com/datasets/zaheenhamidani/ultimate-spotify-tracks-db?select=SpotifyFeatures.csv): This additional dataset provides genre-related information that will enhance our analysis.

   - Make sure to download these datasets and place them in the same directory as the Jupyter Notebook (`Spotify.ipynb`) to ensure smooth execution of the analysis.

3. **Open the Jupyter Notebook:**
   - Launch Jupyter Notebook or a compatible environment.
   - Navigate to the cloned directory and open the Jupyter Notebook file `Spotify.ipynb`.

4. **Execute the Notebook:**
   - Run the cells within the notebook to perform the analysis and generate visualizations.


## Analysis Highlights

Here are some of the key analyses and visualizations performed in the notebook:

- **Popularity Analysis:** Identifying the most and least popular songs on Spotify.
- **Correlation Analysis:** Exploring correlations between various song attributes.
- **Yearly Trends:** Analyzing trends in song releases over the years.
- **Genre Analysis:** Investigating the duration of songs in different genres and identifying the top 5 genres by popularity.


# What's in 'Spotify.ipynb' file???

This GitHub repository contains (`Spotify.ipynb`) file which helps in analyzing and visualizing Spotify music data using popular data science libraries such as NumPy, Pandas, Matplotlib, and Seaborn. The script explores a dataset of music tracks and provides insights into song popularity, correlations between variables, and genre-related information. Below is an overview of the main sections and analyses performed in the script:

## Data Loading and Initial Exploration:

- The script begins by importing necessary libraries and loading a dataset of music tracks from a CSV file (`tracks.csv`).
- Initial data exploration is conducted to check for missing values and get an overview of the dataset's structure.

## Analysis of Popularity:

- The script identifies the most and least popular songs on Spotify based on the "popularity" metric.
- It filters songs with popularity greater than 90 and less than 90, providing separate lists of popular and less popular songs.

## Correlation Analysis:

- A correlation matrix is computed to understand the relationships between various numerical variables (excluding non-relevant columns).
- A heatmap is generated using Seaborn to visualize the correlations between variables.
- ![image](https://github.com/LikhithaAralimara/Spotify-Data-Analysis/assets/128489410/c5fdb317-11b1-4697-94a1-4b6560dd2671)


## Sampling Data:

- A subset of the data is randomly sampled to create a smaller dataset for specific analyses.

## Visualization of Relationships:

- Two scatterplots are created to visualize relationships between song attributes: "loudness" vs. "energy" and "popularity" vs. "duration."
- ![image](https://github.com/LikhithaAralimara/Spotify-Data-Analysis/assets/128489410/804f37e2-7bdc-4c9f-bac4-bbb0ef042184)
- ![image](https://github.com/LikhithaAralimara/Spotify-Data-Analysis/assets/128489410/7e9e2023-4044-466f-aa0e-dbf2f014b8d3)

## Yearly Trends:

- The script extracts the release year from the "release_date" column and explores the trend of increasing song releases over the years.
- A histogram is plotted to visualize the number of songs released per year.
- ![image](https://github.com/LikhithaAralimara/Spotify-Data-Analysis/assets/128489410/dd6ba865-8593-4e43-88e2-c3ae80dd9f37)

- A line plot shows the average song duration over the years.
- ![image](https://github.com/LikhithaAralimara/Spotify-Data-Analysis/assets/128489410/26c064a9-2f0c-4d16-8fc6-cb5a260ef058)


## Genre Analysis:

- An additional dataset (`SpotifyFeatures.csv`) containing genre-related information is loaded.
- A bar plot illustrates the duration of songs in different genres.
- ![image](https://github.com/LikhithaAralimara/Spotify-Data-Analysis/assets/128489410/087e4b03-71c8-4e8a-a461-b02c2e5a5bbf)

- The top 5 genres with the highest popularity are identified and visualized in a bar plot.
- ![image](https://github.com/LikhithaAralimara/Spotify-Data-Analysis/assets/128489410/d96799a6-7fd7-4100-800e-33a1935349e0)


This script serves as a comprehensive analysis of Spotify music data, offering insights into song popularity, relationships between song attributes, and genre-related trends. The visualizations and analyses can help music enthusiasts, data scientists, and researchers gain a better understanding of music trends and preferences on the Spotify platform.

This script serves as a comprehensive analysis of Spotify music data, offering insights into song popularity, relationships between song attributes, and genre-related trends. The visualizations and analyses can help music enthusiasts, data scientists, and researchers gain a better understanding of music trends and preferences on the Spotify platform.
