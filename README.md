MICROSOFT'S NEW MOVIE STUDIO ANALYSIS
Name: Julie chepngeno
introduction
In the realm of entertainment, the magic of movies has captivated audiences for generations.It is within this ever-evolving landscape that a new movie studio emerges, ready to make its mark on the industry.There are several key factors that an analyst may consider when coming up with a new film.These include the studio financial backing,the experience and reputation of their leadearhip team,the target audience and the films marketing strategy. Also identifying potential strengths and weaknesses and anticipate their ability to complete in the crowded market.

We therefore want to figure out what exactly makes a movie a “success”, through analysis so that we can narrow down to some common factors in successful movies.Our target for this project is  the Microoft company where we aim at providing them insights for them to chooe on the films to produce which will in turn attract more cutomers and in turn more profit ratio .

The project will involve analyzing different movies with the aim of finding he most favourable one  will in turn be of key value in making strategic decisions for our studio regarding production and financing.

PROBLEM STATEMENT

Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. You are charged with exploring what types of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

Main objective
The goal of this analysis is to provide an insight for Microsoft regarding the latest box office films and what is popular and most successful so they can leverage this information to provide quality content in their new movie studio

Specific objectives
To translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

To equip the Microsoft's management team with the necessary knowledge to determine the most succeful genres, themes, and strategies for achieving success in this competitive domain.

Notebook Structure
* Data Collection
* Read and check the data
* Cleaning the data
* Explaratory Data Analysis
* Conclusions and Recommendation

Data Undertanding
The data was collected from various locations, the different files have different formats. Some are CSV or TSV files that can be opened using spreadsheet software or pd.read_csv, while the data from IMDB is located in a SQLite database.The data used in this project were downloaded from tn.movie_budgets.csv,title.basics.csv and title.rating.csv 

The data includes different information concerning the movies ranging from the title, genres, average-rating, e.t.c

Analyzing dataset will determine what contributes to the "success" of a movie. In this analysis, I will define analysis in financial terms basing the success of a movie on the amount of money it earns in comparison to the budget.

Methodology
*Data cleaning

Out of the several datasets that were collected, only some features and rows are relevant to the process. Therefore, in this step, the features that are not required from each dataset were dropped.The remaining datasets were then joined

- Exploratory Data Analysis
* From our analysis, we can see that in the top 20 most succesful genres ,the combination of genres; ACTION, DRAMA, ROMANCE had the most in average income ratio
<img src ="images\output.png" />
*Genre Drama is most common in most succesful movies as it appears most in the succesful movies and moreso in the TOP 100. Drama, thriller, comedy appear in both graphs which brings a trend in the genres common in succesful movies.

* The data from the number of votes is skewed as we can see that majority of succesful movies have less than 100,000 votes with the average number votes being 123,205 votes. There is a very huge variance in the number of votes (182,927 votes) due to the very many outliers above 400,000 votes.This tells us that there is no standard number of votes required for the averagerating.<img src = "images\output1.png" />

* There is a correlation coefficient of 0.407 which indicates a low positive correlation. There is a low positive correlation between this two. We can see that the number of votes slightly affect the average rating.From the observations we can tell that there is no standard required number of votes but also we've noticed that a higher number of votes tend to have a slight effect on a high average rating.<img src = "images\output3.png" />

* In the analysis above, we've found out that the best months to release a movie considering the average income ratio, are July, January and November.<img src = "images\output4.png" />

* The data is skewed due to some budget allocations of over 100,000,000 hence pulling the mean upwards.From our findings we can see that the average spending for a succesful movie is around 47,300,000 with most movies being less than 30,000,000.With the median we can tell that a spending within 24,000,000 would be good for a succesful movie.
<IMG SRC = >
CONCLUSIONS
1.From our boxplot, we see there's dual seasonality of higher profits ON July,January and November. The highest profit in summer can be realized during the month of July.
2.Drama,thriller and comedy are likely to attract more viewers
 
RECOMMENDATIONS
1.From our findings,we can see that DRAMA,THRILLER and COMEDY are the most common genres in succeful movies.Therefore i highly recommend the three film genres. Most prefarably DRAMA since it is cheaper to produce and has a high income ratio.
2. The sucess of a movie also highly depends on the release month. I'd also want to recommend three months which proved best in terms of the income generated. They include: **_JULY, JANUARY and NOVEMBER_** with **JULY** having the highest income ratio.
3. I would recommend a budget allocation within 24 million dollars which proved to be a good allocation for a successful movie






