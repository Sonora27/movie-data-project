# Movie Industry Data Analysis

Numen Rubino & Jose Ramirez

Sources: BoxOfficeMojo

## Introduction

Microsoft has decided that they want to enter the movie industry, but they do not know anything about this particular industry. They have tasked us with collecting data on box office revenue and asked us to make recommendations to them on what type of movies they should make based off that data.

Also, we are interested in testing the hypothesis made by comedian Seth Rogen recently that Comedy movies are not simply declining, they have just become bigger budget affairs.

To accomplish this, we scraped data off of BoxOfficeMojo using BeautifulSoup, cleaned it using Pandas, and made visualizations and conclusions using Matplotlib.

## Objectives

* Which genre of movie does the best at the box office?
* Is the Comedy genre in fact declining recently, relative to other genres?
* Has the correlation between budget and profit increased in recent years?
* Are big budget Comedies more successful now than in the past as Seth Rogen has suggested?



## Data Observations

### The Genres With The Most Revenue

![Genres With Most Revenue](https://raw.githubusercontent.com/Mycotic/movie-data-project/master/figures/new-genres-box-office.png)

* The best performing genres are Adventure, Sci-Fi, Action, and Fantasy
* Drama is the worst performing genre while Comedy is a middling performer

### Numbers of Movies Made Each Year by Genre

![Number of Movies Made Each Year By Genre](https://raw.githubusercontent.com/Mycotic/movie-data-project/master/figures/all-genres.png)

* Dramas have declined more than any other genre in recent years
* Comedies are also declining rapidly.

### Correlation Between Budget and Revenue by Year for All Genres

![Correlation Between Budget and Profit](https://raw.githubusercontent.com/Mycotic/movie-data-project/master/figures/%5B'year'%2C%20'worldwide'%5D.png)

* There is in fact an increase in the correlation between budget and revenue for all genres in recent years

### Correlation Between Budget and Revenue by Year by Genre

![Correlation Between Budget and Profit By Genre](https://raw.githubusercontent.com/Mycotic/movie-data-project/master/figures/%5B'Drama'%2C%20'Comedy'%2C%20'Thriller'%2C%20'Action'%2C%20'Adventure'%2C%20'Romance'%2C%20'Crime'%2C%20'Fantasy'%2C%20'Family'%2C%20'Sci-Fi'%2C%20'profit'%5D.png)

* Certain genres such as Action and Adventure have always had a strong relationship between budget and revenue
* Comedies did not used to have a strong relationship between budget and revenue, but that has recently changed

## Conclusions and Recommendations for Microsoft

* Microsoft should make big-budgeted Action and Adventure movies if they are looking to make the biggest splash at the box office
* Seth Rogen's hypothesis that Comedy movies need to have to big budgets in modern times in order to be successful appears to be supported by our data
* Microsoft should capitalize on the current box office market inefficiency on Comedies by making a big-budgeted Comedy
* They would have little competition in the genre and big-budgeted Comedies are experiencing much increased success recently

## Future Work

* Are there any Comedy genre synergies that perform better at the box office than others?
* For example, does an Action Comedy generate better revenue at the box office than an Adventure Comedy?

























