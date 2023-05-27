# MICROSOFT MOVIE STUDIO PROPOSAL ANALYSIS
Aurthor: MARTIN NGUGI.

![Alt text](screenshots/microsoft.jpg)

# OVERVIEW
Microsoft is venturing into the film industry by establishing a new movie studio. With limited knowledge about creating movies, Microsoft aims to gain insights into the types of films that are currently succeeding at the box office. By analyzing the prevailing trends and success factors in the film industry, Microsoft aims to make informed decisions that will guide their film creation process. This exploration is crucial for Microsoft to thrive in the highly competitive market by aligning their strategies with the evolving landscape of the film industry.

# BUSINESS PROBLEM
Microsoft's new movie studio lacks the necessary knowledge and understanding of the film industry to make informed decisions about the types of films to create. This knowledge gap hinders their ability to compete with established companies in producing successful and engaging original content. There is a need for actionable insights into current box office trends and success factors to guide Microsoft's decision-making process and ensure their success in the highly competitive film market.

In order to objectively provide clear recommendations that will be beneficial to Microsoft, the following specific objectives will act as a guide to drawing insights from our datasets.

1. Which studio produces the highest grossing movies. 
2. Find the average runtime of movies and what would be the reccomended runtime for movies to be produces in the studio.
3. What is the relationship between the movie budget and the gross income generated?
4. which is the most preferred original language of a movie.
5. Find the genres with the higest and lowest raatings.

# DATA UNDERSTANDING
The for datasets we'll be working with here are 'bom.movie_gross.csv', 'tmdb.movies.csv', 'tn.movie_budgets.csv', and 'rotten_tomatoes_top_movies.csv'.

1. The 'bom.movie_gross.csv' dataset is a box office dataset showing the domestic and foreign gross revenues of each movie.

2. The 'rt.movie_info.tsv.gz' dataset shows the Runtime of the various movies that has been produced before.

3. The 'tn.movie_budgets.csv' dataset shows production budgets and their corresponding worldwide gross revenue.

4. The 'tmdb.movies.csv' dataset shows the original languages of different movies and their percentage popularity.

5. The 'imdb.title.basics.csv.gz' and 'imdb.title.ratings.csv.gz' datasets were joined together so as to help in in findig the highest and lowest rated genres.

These datasets will help us answer the specific objectives.

## DATA DESCRIPTION
To analyze the data and identify successful film genres, various methods were used. The analysis involved examining box office revenues, movie budgets, and other relevant information, such as genre and release date. Statistical analysis was performed to identify patterns and trends in the data. These methods allowed for a comprehensive analysis of the data and provided actionable insights to guide Microsoft's decision-making process for creating successful films.

## VISUALIZATIONS
1.Relationship between the Production Studios and their Total Revenue made.

 ![Alt text](screenshots/production%20studio%20vs%20Total%20revenue.PNG)
From the above plot we can see that the top 5 Total grossing studios are HC, P/DW, BV, GrtIndia, and WB. These are the companies that Microsoft ne studio should work with to help them get tings right in their production.

2. Average movie run time.

![Alt text](screenshots/avg%20runtime.PNG)

From the above image it is recommended that the average runtime of a movie should be between 100 minutes(mean) and 120 minutes(upper percentile).

3. Comparison between movie production budget and its Net gross income

![Alt text](screenshots/budget%20vs%20w.gross.PNG)

The Scatter plot reveals a moderately positive correlation between the gross income and the budget of a movie, suggesting that an increase in budget tends to result in a higher gross income. This positive relationship implies that by utilizing the insights from our analysis and assembling the appropriate resources, we can potentially gain a competitive edge in our investments and achieve profitability.

4. Preferred language of movie

![Alt text](screenshots/language.PNG)

It can be seen that most movies released, their original language was english.
This is also so since English is the most prefered universal language.

5. Genres with the higest and lowest ratings.

![Alt text](screenshots/top%2015%20genre.PNG)
The above bar plot represents the different types or genres of films and their corresponding ratings. We see that the most highly rated genres include Science Fiction & Fantasy, Action & Adventure, Kids & family, Comedy, Documentaries among other highly rated genres.

![Alt text](screenshots/bottom%2015%20genre.PNG)
The above bar plot represents the poorly performing genres by rating. We see that the poorly rated genres include Horror, History, Romance, War among other poorly rated genres.

# CONCLUSION
After analyzing the data obtained from various sources such as the TMDB dataset, BOM movies, reviews, and movie budgets, several insights were identified to guide Microsoft's decision-making process for creating successful films. The analysis showed that the most successful genres by ratings were action, adventure,comedy, science fiction and Documentaries. The analysis also highlighted the importance of having a high production budget for successful films. These findings provide actionable insights to guide Microsoft's new movie studio in creating successful films and competing in the highly competitive movie industry.

# RECOMMENDATIONS
When coming up with the new Microsoft movie studios I would recommend that:
1. They should strive and work closely or partner with the highest grossing companies in the industry as they could borrow on some of their planning and execution of projets for better return on business.
2. The average run time of a movie being produced should be averagely 100 minutes to 120 minutes.
3. The new studio should invest heavily on their production budget of a movieand with the right resources, this will help in coming up with better movies hence having high prospects on its returns to the business.
4. The new studio shou;d focus more in producing movies with their original language being English.
5. The new studio should produce genres that attract good ratings such as Science Fiction & Fantasy, Action & Adventure, Kids & family, Comedy, Documentaries as it will lead to more viewership which translates to more returns on investment.
