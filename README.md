# Movie Visualizations
## Learn Python for Data Science Portfolio Project


### Overview

This project is one of the portfolio projects on the Data Science pathway at codecademy. In it, I will be inspecting, cleaning, and analyzing a dataset.
With this analysis, I hope to answer questions like:
 - What are the most popular genres, directors, and ratings (R, PG, NC-17, ...)?
 - What is the return ratio for the movies, its average by genre, and its impact on score?
 - How scores, budgets, and runtimes changed across the years
 - Which directors work more often with which stars and which writers
   
The project code and results are contained in the Jupyter Notebook Movie-Data.ipynb, with a summary of the conclusions below.

The libraries and dependencies used were:
Python (3.13.5)
numpy: 2.3.2
pandas: 2.3.2

### Update

Based on feedback, I decided to update the project with some visualizations to help understand the data and make the findings clearer. I'll also be adding some extra analysis of the data and adding some more bullet points to the conclusions at the end.


### The data

The dataset I chose was downloaded from [kaggle.com](https://www.kaggle.com/datasets/ashishkumarjayswal/movies-updated-data/data). It contains a collection of movie-related data, gathered from various sources, including IMDb, over 20 years, from 1980 to 2001.

###  Conclusion
 
I had a lot of fun and made some interesting discoveries while doing this project, and it got me curious to know, if it was a dataset with more recent entries, how would the findings change? I would definitely like to work with a larger and more recent dataset on movies one day, should the opportunity arise.

These are some findings I made during the analysis:

- Titanic is the movie with the biggest budget and gross revenue in our dataset, having a budget of $200M and a gross revenue of $2B.
- Of the top 5 best-scored movies from 1980 to 2001, 4 are from 1994: "The Shawshank Redemption", "Pulp Fiction", and "Schindler's List" in the first three positions and "Forrest Gump" in number 5.
- When analyzing the gross revenue, there is a big jump from the third quartile to the maximum values, with the maximum being almost 62 times the value of the third quartile. This is due to movies that managed to have gross revenue several times their budget, like "Titanic", "The Lion King" or "Jurassic Park".
- The dates with the most simultaneous releases were 14/02/86, Valentine's Day, and 04/10/1991, both with 9 movies released that day, but the best day over all the years to release movies is Christmas Day, with 49 movies released on Christmas, possibly due to people having Christmas breaks and holidays.
- The most frequent genre is Comedy, with 1355 entries, followed by Drama with 807 and Action with 775. The company with the most releases is Universal Pictures with 191 movies, and "R"-rated movies are more frequent with 2043 entries, over half of our dataset!
- Over the years, the average runtimes and score have remained fairly consistent.
- The movie's production budget has increased almost 6 times, while the gross revenue has only increased approximately 3 times, which I found interesting, as I was expecting the gross revenue to have increased more or the same as the budget. This might be because the production companies might be relying more on other sources of revenue like toys, TV airings, memorabilia, etc.
- Both the biggest budget and gross revenue are for "PG-13" and "PG" ratings, which makes sense, as everyone of every age can see them, and this makes a wider audience.
- In genres, "Animation" and "Action" movies are the ones with higher budgets and also higher gross revenue.
- If we take into account the profitability ratio, "Family" and "Horror" movies are the genres with the best ratio, of around 40% gross revenue for their budget, while all other genres remain between 1 and 3.5%. "R"-rated movies also have the best profitability ratio at 6.41%.
- Both Clint Eastwood and Woody Allen starred in movies they were directing 13 and 12 times, respectively, but other than that, the most collaborations between movie directors and actors go to J. Lee Thompson with actor Charles Bronson and Director Richard Dormer with Mel Gibson, with 6 movies each.
- Woody also wrote 21 out of the 22 movies he directed, being the director with the most movies released.
- Woody Allen and Clint Eastwood appear again leading the top of directors working with the same production companies, with Allen collaborating with Jack Rollins & Charles H. Joffe Productions 11 times and Eastwood releasing 8 films with Warner Bros.
- Eastwood is also the main actor in movies from Warner Bros., being the main actor in the 8 movies he directed for that company.
- There is a clear tendency for directors to be the writers of the movies they are directing, but the writer with the most movies released is Stephen King, with 27 movie adaptations.
The most highly scored writers are novelists and writers whose work has been adapted for the big screen, like Thomas Keneally and J.R.R. Tokien.
