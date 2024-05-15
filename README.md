# IMDb Movie Analysis Project

## Group Members
- Alejandro Figueroa
- Raynard Flores
  
## Project Overview
This project aims to analyze IMDb movie data to provide insights into various aspects of the movie industry. Our primary focus is on understanding which movies are most valued by viewers within specific genres and how these preferences correlate with user ratings and vote counts. Additionally, we explore the relationship between a movie's gross earnings and its IMDb rating to determine if higher ratings are indicative of higher earnings, determine which genre (out Action, Animation, Horror, History) generates the most average votes by user, and which one has the longest average runtime.

## Problem Statement
A cinephile was curious to discover significant films within specific genres based on IMDB ratings and vote counts. Being a data analyst, he decided to conjured three hypotheses about these top rated movies in order to use
the techniques he has learned so far: data cleaning, data wrangling, EDA, and data visualization. 

### Specific Goals:
1. Determine the highest rated movies within specific genres based on user ratings and vote counts. The genres that are going to be analysed are:
   - Action
   - Animation
   - Horror
   - History
   - 
2. Analyze the correlation between a movie’s gross earnings and its IMDb rating to understand the factors contributing to a movie's financial and critical success.
3. Of the highest rated movies by genres specified, determine genre which one has the highest average amount of votes.
4. Of the highest rated movies by genres specified, determine genre which one has the highest average runtime.

## Data Description
Our main dataset comes from Kaggle, and essentially is a combination of CSV files that have information about movies with specific genres. 

 - Kaggle Dataset: https://www.kaggle.com/datasets/rajugc/imdb-movies-dataset-based-on-genre

The dataset contains the following columns:
- `movie_id`: IMDb Movie ID
- `movie_name`: Name of the movie
- `year`: Release year
- `certificate`: Movie certificate rating
- `run_time`: Total runtime of the movie
- `genre`: Genre of the movie
- `rating`: IMDb rating of the movie
- `description`: Description of the movie
- `director`: Director of the movie
- `director_id`: IMDb ID of the director
- `star`: Star of the movie
- `star_id`: IMDb ID of the star
- `votes`: Number of votes the movie received on IMDb
- `gross`: Gross box office revenue of the movie in dollars

Our second data source is the Movie Database API, which collects movie information from IMDb and its freely hosted on the RapidAPI page.

  - Movie Database API: https://rapidapi.com/SAdrian/api/moviesdatabase

## Hypotheses
*Here, we will outline our initial hypotheses based on our problem statement. These hypotheses will guide our analysis and help us focus on specific relationships within the data.*

- **Hypothesis 1:** There is a correlation between a movie's IMDB rating and its worldwide gross.
- **Hypothesis 2:** Among the selected common genres—Action, Horror, Animation, and History—we hypothesize that the Action genre generates the highest average number of votes.
- **Hypothesis 3:** Among the selected genres, we hypothesize that the Action genre has the highest average runtime

## Analysis Methodology
We will employ various data analytics techniques including data visualization, EDA, and data wrangling to explore the dataset and validate our hypotheses.

## Results
*This section will be updated with the results of our analysis, including key findings and any insights gained from the exploration of the dataset.*

## Conclusion
*Final thoughts and conclusions will be drawn from the results of the analyses performed, highlighting the implications of our findings on movie viewership and industry trends.*

## How to Contribute
Contributions to this project are welcome. You can contribute by:
- Extending the analysis to include additional movie metrics.
- Improving the predictive models.
- Refining the visualizations and interpretations.

Please refer to the contribution guidelines before making a contribution.

## Presentation Slides
[Link to presentation](https://docs.google.com/presentation/d/1ATmncnO1b7QPUmGnZ4c7Y8uMyYl-sD0tpf9TJMTSLbw/edit?usp=sharing)
