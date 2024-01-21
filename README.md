# Movie-recommender-system

## Exploratory Data Analysis of Movie Data

•Key Findings:

o  The number of movie releases has increased steadily over time, but the success rate of movies has remained relatively constant.\
o  Drama and comedy movies are the most popular genres, followed by thriller and action.\
o  English is the most common language in movies, but there is a growing trend of international films being produced.\
o  Budget and revenue are the two most strongly correlated variables, but there are other factors, such as genre, cast, and marketing, that also play a role in movie success.

•Implications for Business Decisions:

o  Studios can use the insights gained from EDA to make more informed decisions about which movies to produce and how to market them.\
o  For example, the finding that movies with higher budgets tend to have higher revenues suggests that studios should focus on investing in high-quality films.\
o  Additionally, the finding that action and adventure movies are the most popular genres suggests that studios should focus on producing more of these types of films.

•Conclusion:

EDA is a powerful tool for understanding data and gaining insights, by applying EDA to movie data from TMDB, I was able to learn more about the industry, identify trends and patterns, and develop a better understanding of the factors that contribute to movie success.


## Creating The Recommender System: `Movie Recommender System: Unveiling Hidden Movie Gems`

In the world of data science, recommending items based on user preferences is a valuable tool. My recent project, a movie recommender system, explores this area, using data preprocessing and vectorization techniques to uncover hidden movie gems.

First, I carefully cleaned up the data, removing unnecessary columns and converting JSON-formatted data into lists. Columns with similar attributes were merged, creating a cleaner dataset for analysis.

Next, I used vectorization making the vector of each movie. Stemming techniques further improved this process, reducing words to their root forms for better comparisons.

To measure movie similarity, I used cosine similarity, which calculates the angle between vectors, indicating how close they are. With this measure, the system could identify the top five most similar movies to any given input.

The resulting recommender system demonstrates the power of data science in uncovering hidden connections and providing personalized recommendations. From movie buffs to casual viewers, this tool can enhance the movie-watching experience for everyone.

