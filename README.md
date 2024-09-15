# Movie Recommendation System

This repository contains a movie recommendation system implemented using Python. The system suggests movies similar to a given movie based on user ratings, leveraging collaborative filtering techniques.

## Description

The movie recommendation system utilizes the MovieLens dataset to recommend movies that are similar to a specified movie. The recommendation is based on user ratings and is calculated using correlation metrics. The system filters recommendations based on the number of ratings a movie has received to ensure the quality of recommendations.

## Files

- `dataset.csv`: Contains user ratings data in tab-separated format with columns `user_id`, `item_id`, `rating`, and `timestamp`.
- `Movie_ID_Titles.csv`: Contains movie titles corresponding to the `item_id`.
- `recommendation_system.py`: Python script implementing the recommendation system.

## Requirements

To run this project, you need the following Python libraries:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`

You can install the required libraries using pip:

```bash
pip install numpy pandas matplotlib seaborn
