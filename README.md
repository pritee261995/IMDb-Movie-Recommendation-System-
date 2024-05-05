# IMDb-Movie-Recommendation-System-

# 1) Business Objective:
Scraped data from IMDB to analyze and build a movie recommendation system.
The system provides insights into movie attributes and suggests similar movies based on user preferences.

# 2) Dataset Details:
Contains information on the top 10,000 movies listed on IMDb.
Attributes include movie name, release year, rating, metascore, gross income, votes, runtime, genre, certificate, description, directors, and stars.

# 3)Data Cleaning and Analysis:
Identified and treated missing values in the dataset.
Conducted exploratory data analysis to understand distributions and patterns.
Utilized histograms and bar plots to visualize distributions and trends.
Identified outliers and skewed distributions.

# 4)Feature Engineering:
Extracted relevant features for recommendation: genre, director, stars, and description.
Combined features to create a comprehensive set of movie tags.
Applied stemming to normalize text data for better processing.

# 5) Recommendation Algorithm:
Utilized TF-IDF vectorization to convert text data into feature vectors.
Calculated cosine similarity between movie vectors to measure similarity.
Developed a function to recommend similar movies based on user input.

# 6) Deployment:
Deployed the recommendation system on Streamlit, Flask, and AWS.
Users can access the system, input a movie, and receive personalized recommendations.
Insights from Visualization:

# 7)Genre Analysis:
Identified "Drama" as the most popular genre.
Observed a saturation point after "Drama Mystery Romance."

# 8) Year of Release Analysis:
Highlighted fluctuations in movie releases over the years.

# 9) Certificate Analysis:
Recommended focusing on "TV-13" certified series based on high ratings.
Duration vs. Certificate Analysis:
Noted higher ratings for "18+" certified movies due to longer durations.

# 10) Gross Analysis:
Identified "Incredibles 2" as the highest-grossing movie.
Noted that sci-fi movies tend to have higher gross incomes.

# 11) Future Scope:
Implement user feedback mechanisms to enhance recommendation accuracy.
Incorporate collaborative filtering or deep learning techniques for more advanced recommendations.
