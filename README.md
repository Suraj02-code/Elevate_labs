# data-cleaning-task1
Netflix Dataset — Cleaned Version

This repository contains a cleaned version of the Netflix dataset, which includes details about Movies and TV Shows available on the platform. The dataset includes attributes such as title, type, cast, director, country, date added, release year, and more. The data has been cleaned and prepared for analysis using Microsoft Excel.

Data Cleaning Summary

The following data cleaning steps were performed to prepare the dataset for analysis:

- Removed exact duplicate rows
- Filled missing values in critical columns (e.g., country filled with 'Unknown' where missing)
- Standardized text in categorical fields (e.g., type: Movie / TV Show)
- Cleaned inconsistent capitalization (e.g., titles, countries)
- Ensured column names are consistent and readable
- Checked and retained duration values as-is (since they include both minutes and seasons)
- Date_added column kept in string format (not converted to date type)

Dataset Fields

The dataset contains the following fields:

show_id — Unique ID for each show  
type — Type of show (Movie or TV Show)  
title — Title of the show  
director — Director of the show  
cast — Main actors/actresses  
country — Country of origin  
date_added — Date it was added to Netflix (in string format)  
release_year — Year of release  
rating — Age rating (e.g., TV-MA, PG)  
duration — Length of the show (in minutes or number of seasons)  
listed_in — Genres or categories the show belongs to  
description — Summary of the show/movie

Tools Used

Microsoft Excel  
(Optional: Power BI / Tableau / Python — depending on next steps)

Next Steps (Ideas)

- Visualize data by release year, genre, or rating  
- Analyze trends over time (e.g., number of shows released per year)  
- Identify top directors or most active countries  
- Explore genre distribution (e.g., how many shows are comedy, drama, etc.)

Feel free to clone or fork this repository and explore the dataset further.
