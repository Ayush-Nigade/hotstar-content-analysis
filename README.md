# Hotstar Content Analysis

This project explores and visualizes content trends on Disney+ Hotstar using Python and pandas. The goal is to understand how content types, genres, seasons, and episodes are distributed and how these patterns evolve over time.


## Problem Statement

Analyze a dataset from Disney+ Hotstar to uncover:

1. Distribution of content types (Movies vs TV Shows)
2. Genre frequency and how it varies by content type
3. Evolution of content production over the years
4. Popularity trends of top genres across time
5. Structural patterns in TV shows (seasons & episodes)


##  Dataset

- **File**: `hotstar.csv`
- **Source**: kaggle
- **Size**: 6874 rows × 10 columns  
- Dataset contains 10 attributes with simple meaning and which are described as follows:
     hotstar_id: ID of tv show and movie.
     title: Title/Name of tv show and movie.
     description: Short Description describing content.
     genre: Genre of content.
     year: Release year of content.
     age_rating: Age Rating. (as listed)
     running_time: Running time of movie.(in minutes)
     season: Number of seasons of tv show.
     episodes: Number of episodes of tv show.
     type: Content is Tv show or Movie.
     This files contains 6245 unique tv show and movies.
     
     

##  Data Preprocessing Steps

- Null values replaced with `0` where applicable
- Unnecessary columns removed: `age_rating`, `description`, `hotstar_id`, etc.
- Converted `year` to datetime format for time-based analysis
- Cleaned column names and trimmed whitespace characters (e.g., `type\r` ➝ `type`)



##  Technologies Used

- **Language**: Python
- **Libraries**:  
  - `pandas` – data manipulation  
  - `matplotlib` & `seaborn` – visualizations  
- **Platform**: Jupyter Notebook / Google Colab  
- **Version Control**: Git + GitHub



##  Key Insights

- **Movies dominate** the platform's catalog, but TV shows cover niche genres.
- **Drama** and **Comedy** are the most versatile and frequently occurring genres.
- Content production **increased sharply post-2015**, indicating OTT growth.
- Some genres have **volatile popularity**, possibly influenced by trends or limited series.
- **TV genres like Drama and Reality** have significantly higher episodes and seasons on average.

