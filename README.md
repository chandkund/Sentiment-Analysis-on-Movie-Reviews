# Sentiment-Analysis-on-Movie-Reviews
Project on Sentiment Analysis of Movie Reviews using K-means clustering. This project clusters movie reviews based on their sentiment scores to understand audience reactions. Includes data preprocessing, feature selection, model development, and visualization.
## Project Workflow
 1. Exploratory Data Analysis (EDA)
Analyzed the distribution of IMDB_Rating and Gross.
Visualized the data to identify patterns, anomalies, and correlations.
Handled missing values and duplicates to ensure clean data for analysis.
 2. Data Preprocessing
Standardized the features using StandardScaler to ensure proper clustering.
Handled missing values and removed duplicates to maintain data integrity.
 3. K-Means Clustering
Implemented K-Means clustering to group movies based on their IMDB_Rating and Gross.
Determined the optimal number of clusters using the Elbow Method and applied sentiment labels (Negative, Neutral, Positive) to each cluster based on cluster centers.
 4. Visualization and Interpretation
Annotated the plot with sentiment labels to provide insights into the clustering results

## Datasets
The dataset includes the following columns:

- Poster_Link: URL of the movie's poster.
- Series_Title: Title of the movie.
- Released_Year: Year the movie was released.
- Certificate: Movie rating certificate (e.g., PG, R).
- Runtime: Duration of the movie.
- Genre: Genre of the movie.
- IMDB_Rating: IMDB rating of the movie.
- Overview: Brief description of the movie.
- Meta_score: Metacritic score of the movie.
- Director: Director of the movie.
- Star1, Star2, Star3, Star4: Leading stars in the movie.
- No_of_Votes: Number of votes the movie received on IMDB.
- Gross: Gross earnings of the movie.


## Table of Contents
- [Datasets](#datasets)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [License](#license)
- 
## Installation
1. **Clone the repository**:
    ```bash
    git clone https://github.com/chandkund/Sentiment-Analysis-on-Reviews.git
    ```
2. **Navigate to the project directory**:
    ```bash
    cd Sentiment-Analysis-on-Reviews
    ```
3. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To run the analysis, execute the following command:
```bash
python sentiment_analysis.py
```

## Results
The project successfully categorized movies into sentiment clusters (positive, neutral, and negative), highlighting the correlation between IMDB ratings and box office performance.


## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.





















