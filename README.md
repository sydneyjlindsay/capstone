# Capstone Project 

### Project Overview
This project aims to predict IMDb star ratings for movies and shows based on features like review text, genre, duration, and more. The focus is on the film and television sectors, especially in the context of the ongoing "streaming wars."

### Problem Statement
As traditional studios and streaming services vie for audience attention, understanding consumer sentiment quickly is critical. This project aims to model star ratings and analyze trends, offering a competitive edge to various stakeholders.

### Target Audience
This analysis benefits movie producers, streaming platforms, advertisers, and viewers by providing actionable insights for decision-making and personalization.

### Key Features
The project leverages Natural Language Processing and machine learning models to predict star ratings based on a myriad of features, providing a more nuanced understanding of audience sentiment.

### Impact
In an industry where billions are at stake and sentiment is continuously evolving, this project could be a game-changer. It aims to influence content creation, improve advertising targeting, and offer better recommendations to consumers

## Notebooks

- **1-Cleaning_MovieLens_Dataset**: 
  - Start here. Cleaning the main MovieLens Dataset of user review text. 
  
- **2-Cleaning_Supplemental_Metadata**: 
  - Cleaning supplemental movie metadata dataset. 
  
- **3-EDA**: 
  - Exploratory Data Analysis and final cleaning of dataset.

- **4-Baseline_Modeling**: 
  - Final dataframe creation, feature engineering, text pre-processing, and baseline modeling. 
  
- **5-Further_Baseline_Modeling**: 
  - Re-approaching feature engineering with different methods, re-doing text vectorization, and running further baseline models. 

## Data Dictionary

- **imdb_id**: 
  - IMDb's unique identifier for each movie or show.
  
- **title**: 
  - The title of the movie.
  
- **actors**: 
  - List of main actors in the movie or show.

- **directors**: 
  - List of directors who worked on the movie.

- **genres**: 
  - List of genres associated with the movie.
  
- **language_en**: 
  - Whether the original language was English (1) or other (0).
  
- **year**: 
  - The year the movie was released.
  
- **runtime**: 
  - The duration of the movie in minutes.
  
- **budget**: 
  - The production budget of the movie.
  
- **box_office_gross**: 
  - The total box office gross of the movie.
  
- **production_companies**: 
  - List of production companies involved in the movie.
  
- **votes**: 
  - The number of votes that the movie has received on IMDb.
  
- **rating**: 
  - The IMDb star rating of the movie out of 10.

*Note: directors, actors, production_comapnies are listed in order of "credit" (importance) as per the official movie credits. Genres are listed alphabetically.*


    