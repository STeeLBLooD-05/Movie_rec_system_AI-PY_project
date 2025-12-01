# Movie Recommendation System

## Overview
This project is a content-based movie recommendation system built in Python using Jupyter Notebook. It suggests movies similar to a given movie based on features like genres, keywords, tagline, cast, and director.

## Features
- Uses TF-IDF vectorization to convert text data into feature vectors
- Employs cosine similarity to measure similarity between movies
- Handles user input for movie names and finds the closest match
- Outputs a list of top movie recommendations

## Prerequisites
Before running the project, ensure you have the following installed:

- Python 3.x
- Jupyter Notebook or JupyterLab
- Required Python libraries:
  - numpy
  - pandas
  - scikit-learn
  - difflib

## Dataset
The system uses a CSV file named `movies.csv` containing movie data with columns such as:
- title
- genres
- keywords
- tagline
- cast
- director
- overview
- etc.

Make sure the `movies.csv` file is in the same directory as the notebook.

## How to Run
1. Clone or download the project files.
2. Open a terminal or command prompt.
3. Navigate to the project directory.
4. Install required libraries (if not already installed):
5. Launch Jupyter Notebook:
6. Open the `Movie_recc_system.ipynb` notebook.
7. Run the cells sequentially.
8. When prompted, enter a movie name (e.g., "Iron Man") to get recommendations.

## Project Structure
- `Movie_recc_system.ipynb`: Main Jupyter Notebook containing the code
- `movies.csv`: Dataset file (required)
- `README.md`: This file

## Example Usage
Enter your favourite movie name : Iron Man

Close matches found: ['Iron Man', 'Iron Man 3', 'Iron Man 2']
Using: Iron Man

Recommended movies:

Avengers: Age of Ultron

The Avengers

Iron Man 2

Iron Man 3

Captain America: Civil War

## How It Works
1. **Data Loading & Preprocessing**: The dataset is loaded and relevant text features are combined.
2. **Vectorization**: Text data is transformed into TF-IDF feature vectors.
3. **Similarity Calculation**: Cosine similarity is computed between movies.
4. **User Interaction**: The user inputs a movie, and the system finds the closest match.
5. **Recommendation**: Movies with the highest similarity scores are displayed.

## Notes
- Ensure the dataset file is correctly formatted and placed in the same folder.
- The system is case-insensitive and can handle minor typos in movie names.
- Recommendations are based solely on textual content (no collaborative filtering).

## License
This project is for educational purposes. Feel free to modify and distribute.