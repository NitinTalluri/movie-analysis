# movie-analysis

About Dataset
Context
Is the movie industry dying? is Netflix the new entertainment king? Those were the first questions that lead me to create a dataset
focused on movie revenue and analyze it over the last decades. But, why stop there? There are more factors that intervene in this
kind of thing, like actors, genres, user ratings and more. And now, anyone with experience (you) can ask specific questions about the
movie industry, and get answers.

Content
There are 6820 movies in the dataset (220 movies per year, 1986-2016). Each movie has the following attributes:

budget: the budget of a movie. Some movies don't have this, so it appears as 0

company: the production company

country: country of origin

director: the director

genre: main genre of the movie.

gross: revenue of the movie

name: name of the movie

rating: rating of the movie (R, PG, etc.)

released: release date (YYYY-MM-DD)

runtime: duration of the movie

score: IMDb user rating

votes: number of user votes

star: main actor/actress

writer: writer of the movie

year: year of release

I have conducted a detailed analysis of a movie dataset, focusing on various data cleaning, preprocessing, and manipulation steps to enhance the dataset's readability and reliability. The steps undertaken included:

Data Cleaning: Identified and handled missing values, outliers, and inconsistencies within the dataset.
Data Preprocessing: Standardized data formats, normalized numerical data, and encoded categorical variables.
Data Manipulation: Aggregated data, created new relevant features, and removed redundant columns to streamline the dataset.
Upon concluding the analysis, I compared different variables with the gross revenue of movies to identify significant correlations. My findings are as follows:

There is a high correlation between gross revenue and both votes and budget. This indicates that movies with higher budgets and more votes tend to have higher gross revenues.
Conversely, there is a lower correlation between gross revenue and company. This suggests that the production company has less impact on the gross revenue of a movie.
My initial prediction, which posited a higher correlation between score (presumably the movie's rating) and gross revenue, was incorrect. The data analysis revealed that score does not have as strong a correlation with gross revenue as votes and budget do.
These insights underscore the importance of certain factors like budget and audience engagement (votes) in determining a movie's financial success, while aspects like the production company and movie rating are less influential.

