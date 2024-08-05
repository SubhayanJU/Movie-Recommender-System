# Movie-Recommender-System

## Project Overview

This project presents a movie recommender system designed to suggest five similar movies based on a given movie name. Using natural language processing (NLP) techniques and machine learning algorithms, this system delivers accurate and relevant movie recommendations.

## Key Features

- **Natural Language Processing (NLP)**: Leveraging the nltk library to process movie descriptions and other textual data.
- **CountVectorizer**: Converting text data into numerical vectors using the CountVectorizer function.
- **Cosine Similarity**: Utilizing cosine similarity to measure the similarity between movies based on their textual representations.
- **Model Serialization**: Saving the trained model using pickle for efficient deployment and usage.

## Methodology

1. **Data Preprocessing**: Cleaning and preparing the movie dataset, including text normalization and tokenization using nltk.
2. **Vectorization**: Transforming the textual data into numerical vectors using CountVectorizer.
3. **Similarity Calculation**: Computing cosine similarity between movie vectors to identify similar movies.
4. **Recommendation System**: Implementing a function to suggest five similar movies based on the input movie name.
5. **Model Serialization**: Saving the trained model using pickle for later use.

## Results

The recommender system shows excellent results in suggesting relevant and similar movies, enhancing the movie-watching experience for users.
## How to Use

1. Clone the repository:
    ```sh
    git clone https://github.com/SubhayanJU/movie-recommender-system.git
    ```
2. Navigate to the project directory:
    ```sh
    cd movie-recommender-system
    ```
3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```
4. Run the recommender script or Jupyter notebook to input a movie name and get recommendations:
    ```sh
    python recommend.py
    ```
    or open the notebook in the `notebooks/` directory and follow the instructions.

## Acknowledgements

- Dataset provided by TMDB.
- Libraries and tools used: nltk, scikit-learn, and pickle.
