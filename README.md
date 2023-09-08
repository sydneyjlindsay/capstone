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

## Data Dictionary

- **item_id**: 
  - Unique identifier for each item (movie or show) in the dataset.
  
- **imdb_id**: 
  - IMDb's unique identifier for each movie or show.
  
- **title_x**: 
  - The title of the movie or show, as sourced from one dataset.
  
- **title_y**: 
  - The title of the movie or show, as sourced from a different dataset.
  
- **rating**: 
  - The IMDb star rating of the movie or show out of 10.
  
- **votes**: 
  - The number of votes that the movie or show has received on IMDb.
  
- **release_date**: 
  - The date the movie or show was released.
  
- **runtime**: 
  - The duration of the movie or show in minutes.
  
- **budget**: 
  - The production budget of the movie or show.
  
- **revenue**: 
  - The total box office revenue of the movie or show.
  
- **original_language**: 
  - The original language in which the movie or show was produced.
  
- **genre_names**: 
  - List of genres associated with the movie or show.
  
- **director_names**: 
  - List of directors who worked on the movie or show.
  
- **directedBy**: 
  - List of directors (sourced from a different dataset).
  
- **actor_names**: 
  - List of main actors in the movie or show.
  
- **starring**: 
  - List of main actors (sourced from a different dataset).
  
- **company_names**: 
  - List of production companies involved in the movie or show.

*Note: Duplicate columns like title_x and title_y, director_names and directedBy, actor_names and starring, will be reconciled later.*