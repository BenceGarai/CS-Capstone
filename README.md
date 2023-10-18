# Movie Recommendation System

This project is an implementation of a Movie Recommendation System using Jupyter Notebook and Python. It utilizes a large dataset of movies, performs data wrangling and cleaning, employs the K-means clustering algorithm to cluster movies, and vectorizes movie descriptions to calculate cosine similarity. With the computed similarity scores and K-means clustering results, it provides movie recommendations to users based on the title of a movie they input.

## Overview

The Movie Recommendation System is a practical application of machine learning and natural language processing (NLP) techniques. It allows users to discover new movies similar to their preferences, making movie recommendations more personalized.

The key components of this project include:

1. **Data Wrangling and Cleaning**: The raw movie dataset is processed to handle missing values, duplicate entries, and any other data quality issues. This ensures that the data is ready for analysis and modeling.

2. **K-Means Clustering**: The K-means clustering algorithm is used to group similar movies together. This helps in categorizing movies into clusters based on their features.

3. **Cosine Similarity**: Movie descriptions are vectorized using NLP techniques, and cosine similarity is calculated between movie descriptions. This allows us to measure the similarity between movies based on their textual descriptions.

4. **Recommendation Generation**: When a user provides the title of a movie, the system identifies the cluster to which the movie belongs and recommends other movies within the same cluster. Additionally, it suggests movies that are similar to the input movie based on their textual descriptions.

## Requirements

Before running the Jupyter Notebook, make sure you have the following libraries and tools installed:

- Python 3.x
- Jupyter Notebook
- pandas
- scikit-learn
- numpy
- Other necessary Python libraries

You can install these libraries using `pip` or `conda` as follows:

```bash
pip install numpy pandas matplotlib scikit-learn seaborn
```
## Usage

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/BenceGarai/AI_Capstone.git
   ```
2. Launch Jupyter Notebook and open the MovieRecommendation.ipynb file.
3. Follow the instructions provided in the notebook to perform movie recommendations based on user input.

# Data Source
The dataset of movies used in this project is sourced from Kaggle.
