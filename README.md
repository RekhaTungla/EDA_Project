# EDA_Project
This is my First EDA project with Python for Exploratory Data Analysis of on 1000 Movies Dataset.
Introduction
Problem Statement
Installing & Importing Libraries
3.1 Installing Libraries
3.2 Upgrading Libraries
3.3 Importing Libraries
Data Acquisition & Description
Data Pre-Profiling
Data Pre-Processing
Data Post-Profiling
Exploratory Data Analysis
Summarization 9.1 Conclusion 9.2 Actionable Insights
 
 
 # Introduction
According to the movie industry statistics, six to seven movies out of ten movies gets unprofitable, only one third of the movie gets success.
Let's Analyse the Movie sucess Mantra with EDA .Isn't it interesting....Now more dig deepar the problem  statement.

# Problem
What are the Director role play in the industry's growth with total number of movies made and Revenue earned in overall market ?

Analyze Trend between Average Revenue and Average Rating (Popularity) of movies over the years ?

Genre combinations which earn high Revenues and Rating and Critics Scores ?

Future planning to add new services and enhance the quality of existing services.

We need  to help in publish Movie Success Mantra to  Magazine , news Articles / blog and  Digital mode services like YouTube / Netflix / Amazon.

Before we start EDA we need to get raw dataset and perform the data cleaning , wrangling, remove unnecessary, duplicate removal.  
Install and import all required Libraries 
Perform Data Acquisition & Description
Data Pre-Profiling and post profiling with Python Pandas libararies.
Ask right Questions like 
  a. Uni Theme
	b. Bi Variate
	c. Multi Variate

Description of the Dataset
The dataset consists of the information about movies from all over the world, mostly US but do notice some indian movies as well listed. Various variables present in the dataset includes data of Title, Genre, Director, Actor, Runtime, Rating, Reveue etc.
The dataset comprises of 1000 observations of 12 columns. Below is a table showing names of all the columns and their description.
Column Name	Description
Rank	Movie Rank
Title	Title of the movie
Genre	The various Genre that the movie can be associated with.
Description	Short description about the movie
Director	Director of the movie
Actors	Main actors in the movie
Year	Year in which the movie was released
Runtime (minutes)	Total movie playing time
Rating	Movie rating
Votes	Votes for the movie
Revenue (Millions)	Revenue by the movie (in millions)
Metascore	Is the score of the movie on the metacritic website by critics

# EDA
Number of variables: 12
Number of observations: 1000
Missing cells: 192 (1.6%)
Numeric = 7
Categorical = 5

After  handling missing values using Median and removing unnessarry columns like description Actors our dataset remains like this :-
Dataset Shape :  (936, 10)
Number of observations: 936

Missing cells: 0 (0.0%)

Variables types:

Numeric = 7

Categorical = 3

With the help of Seaborn , matplotlib Plot packages we perform data analysis inform of Visualiastion like this:
Histogram
Bar graph
Scatter Plot
HeatMap
Donut Charts/Pie Chart
Line plot / KDE /Area graph 
Violinplot
Word Cloud 



# Conclusion  
Concluding our analysis in this section.

The best directors were found out on the basis of Revenue generation, Ratings and Critic scores.
James Cameron : Revenue Christopher Nolan : Rating Barry Jenkins : Metascore Upon analysing the directors of 2016 movies, it was found that None of these top ranking directors made movies in that year. In fact, out of the top 5 list in every category, only Makoto Shinkai (High Rated) had released his film in 2016.

Runtime of movies were analysed.
It was found that movies with Long duration (> 123 mins) did exceptionally well in terms of Revenue generation, and also did better than the rest in terms of Ratings and Critic scores But, only 16.8% long movies were made in 2016. This was a very big opportunity missed in terms of generating Revenue and also making people and critics pleasing movies.

Genres of movies were analysed to find a trend.
As the genre_size (numbers of genres present in a movie) increased, the rating and metascore increased. But, Revenue, significantly increased for genre_size = 3. 58.6% movies in 2016 had a genre combination of 3. Adventure,Drama,Fantasy - Most popular genre that earned the highest Revenue. Animation,Drama,Fantasy - Most popular genre that earned the highest User Rating. Drama,Fantasy,War - Most popular genre that earned the highest Metascore. But in the year 2016, the number of movies made in these genres is as follows: Adventure,Drama,Fantasy : 0 Animation,Drama,Fantasy : 1 Drama,Fantasy,War : 0

We found out Directors of most popular genre movies:
David Yates made the highest Revenue genrating movie in the genre - Adventure,Drama,Fantasy. Makoto Shinkai made the highest Rated movies in the genre - Animation,Drama,Fantasy. Guillermo del Toro made the most critically acclaimed movie in the genre - Drama,Fantasy,War.

The industry's growth is very promising with respect to the number of movies made and Revenue earned. It has grown around 15% in 10 years (from 2006 to 2016).
Having said that, Average Revenue and Average Rating (Popularity) of movies have shown a Negative Trend. This is can be credited to the following facts: With an increase in the number of movies produced each year, the competitionn increases and the movies will need an extra edge to stand out in this tough competition. With time, people's life has become very busy and stressful, they turn to Entertainment for stress busting. And the movie needs to look promising, to attract their attention. No one can afford to waste their time and money on a weak Due to numerous options available, the movie has to stand out in terms of the above mentioned factors to hold people in place. the film has to be as close to perfection as possible as the attention span of people has also reduced with time. It is important to give them something to make them stay till the end.

Rating and Metascore are highly correlated. It means that Audience and Critics think along similar lines. Movies with high Ratings and Metascore have also earned high Revenue, which does make sense and is very natural.

# Actionable Insights 

A successful movie is evaluated by its popularity, vote average score(Ratings) and revenue. Movies need to be strategically plannned to be more appealing to audience and critics, which will in turn result in higher Revenue. The following are some suggested features which need to be worked upon:

Making movies with well acclaimed directors will bring in more Revenue, better Ratings and Metascore.

We know from analysis that Long movies ( >123 mins) have had better Ratings, Metascore and high Revenues.

Genre size plays an important role too. Movies with 3 Genre combination have been very well acclaimed.The most popular genres found are : Adventure,Drama,Fantasy,Animation,Drama,Fantasy and Drama,Fantasy,War. They have proved to be very engaging.

Movies that are audience and critics pleasing, earn more Revenue.

While the pandemic has hit the movie industry hard, it also offers an opportunity for the business models of a time-honored tradition to loosen up and better meet the challenges of the digital world. Streaming is becoming a necessity, following fundamental shifts in content distribution and on-demand audiences.

Navigating these shifts can require time and patience, and may challenge traditional ways of developing, distributing, and monetizing content. Media and entertainment companies able to see the opportunities in change and the value of thinking differently can be empowered to help define the fast-approaching future.




 




