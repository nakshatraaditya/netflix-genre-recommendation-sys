# Netflix Recommendation System

This repository contains the code and resources for a Netflix Recommendation System, developed as a capstone project. The system leverages machine learning techniques to recommend movies to users based on their preferences, genres, and predicted ratings.

## Project Overview

The Netflix Recommendation System is designed to provide personalized movie recommendations for users based on their viewing history, genres of interest, and user-specific ratings. The project uses multi-hot encoding to handle genres and various filtering techniques to enhance recommendations.

### Features
- **User-based Recommendations**: Provides personalized movie recommendations based on user preferences.
- **Genre-specific Recommendations**: Extracts top recommendations across different genres.
- **Multi-Hot Encoding for Genres**: Utilizes multi-hot encoding for efficient handling of genre-based recommendations.
- **Collaborative Filtering**: Predicts user ratings for unseen movies using collaborative filtering techniques.

## Dataset

The project uses a dataset of movies and user ratings. Each movie entry contains details such as:
- Movie ID
- Title
- Genres

Additionally, user-specific ratings data is used to train the model.

## Setup and Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/nakshatraaditya/netflix-genre-recommendation-sys.git
   ```
2. **Install Required Packages**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Data Preparation**: Ensure the dataset files are placed in the `data/` folder and are properly pre-processed.

## Usage

To run the notebook, open the `Netflix(Capstone).ipynb` file and execute each cell sequentially. Below are some key steps to follow:

1. **Data Loading and Preprocessing**: Load and preprocess the dataset by running the initial cells in the notebook.
2. **Model Training**: Train the collaborative filtering model to predict ratings.
3. **Genre Extraction**: Identify unique genres and filter movies by genre.
4. **Recommendation Generation**: For a given user, generate a list of recommended movies across different genres.

## Code Structure

- `Netflix(Capstone).ipynb`: The main Jupyter notebook containing code for data preprocessing, model training, and generating recommendations.
- `data/`: Folder for storing datasets, including movie and rating data files.
- `requirements.txt`: List of required Python libraries for easy installation.

## Key Functions

- **Multi-Hot Encoding for Genres**: Handles the encoding of genres to enable efficient filtering and recommendation.
- **Recommendation Logic**: Uses collaborative filtering techniques to predict user ratings for unseen movies.
- **Genre-Based Recommendations**: Filters movies by genre and selects top-rated movies for each genre.

## Results

The system outputs a list of top-rated movies for each genre based on the user's preferences, providing a customized movie-watching experience.

## Contributing

Contributions are welcome! If you'd like to improve the model, enhance filtering techniques, or add new features, please feel free to open a pull request.

## License

This project is licensed under the MIT License.

## Acknowledgments

- [Netflix](https://www.netflix.com/) for inspiration.
- Datasets used from [MovieLens](https://grouplens.org/datasets/movielens/).

