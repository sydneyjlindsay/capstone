## Predictive Cinematics: An Ensemble Learning Approach

#### Overview
This project aims to predict the success of movies based on a range of features, including both metadata and text-based variables such as reviews. The ultimate goal was to create a model that could take into consideration various movie attributes like actors, directors, genres, and budgets, as well as sentiment from text reviews, to predict a movie's success.

#### Methodology
The dataset comprises several features, including but not limited to:
- Metadata: Actors, Directors, Genres, Budgets
- Text Data: Reviews (processed into unigrams and bigrams)

The project employs various machine learning algorithms, including:
- Logistic Regression
- Random Forest
- XGBoost
- Ensemble Methods (Voting and Stacking Classifiers)

#### Future Directions
1. Feature Engineering: Experiment with different encoding techniques for high-cardinality features like actors and directors.
2. Neural Networks: Investigate the use of neural networks and embedding layers to capture more complex relationships among the features.

---

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
  
- **6-Final_Modeling**: 
  - Final modeling and hyperparameter tuning, along with model evaluation and interpretation.   

- **final_modeling_separate**: 
  - Original individual notebooks for final models, originally run in colab. 
  
---
  
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