# movie-recommender-system-tmdb-dataset

This is a movie recommendation system built using content-based filtering. The system recommends movies similar to a selected movie based on their features such as title, overview, genres, keywords, cast, and crew.

## Data

This project uses a dataset from Kaggle (https://www.kaggle.com/tmdb/tmdb-movie-metadata) to build a movie recommendation system. The dataset contains information on over 5000 movies, including movie title, overview, genres, keywords, cast, and crew.


## Methodology
1. Feature Selection: Selected important features from the movies dataset such as movie_id, title, overview, genres, keywords, cast, and crew.
2. Text Cleaning: Applied text cleaning techniques to the text features such as removing spaces and converting the data into a usable format.
3. Vectorization: Applied CountVectorizer to convert text features into numerical representations.
4. Similarity Calculation: Calculated cosine similarity between movies based on their numerical feature representations.
5. Recommendation Generation: Generated movie recommendations by selecting movies with the highest cosine similarity values.

## Usage

1. Clone the repository to your local machine.
2. Install the required libraries by running pip install -r requirements.txt.
3. Run the Streamlit app by executing streamlit run app.py in your terminal.
4. Select a movie from the dropdown menu and click the "Recommend" button to generate a list of recommended movies.

## Files

- data: Folder containing the dataset used for the project.
- notebooks: Folder containing Jupyter Notebooks used for data cleaning and analysis.
- app.py: Python file containing the Streamlit app code.
- movie_list.pkl: Pickle file containing the preprocessed movie data.
- similarity.pkl: Pickle file containing the cosine similarity matrix between movies.
- README.md: Markdown file containing information about the project.

## Credits

This project was developed by Gaurav Purohit and is based on the dataset from Kaggle: https://www.kaggle.com/tmdb/tmdb-movie-metadata.

## License

This project is licensed under the MIT License.

### Video Documentation: https://youtu.be/4PI7bZlk1Gw
### Model for web hosting: https://github.com/gaurav9799/Movie-Recommendation-System/blob/main/app.py
