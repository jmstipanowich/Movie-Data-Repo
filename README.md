# Microsoft in the Movie Industry

Author: James Stipanowich

![IMDb movie picture](MovieDataImages/TVlanding.png)

## Introduction/Overview

Microsoft wants to create movies, but their movie knowledge is limited. They want knowledge about the movie industry from me. This project explores three questions Microsoft might ask me about movies and the movie industry from a specified given group of movie datasets. Movies that do well at the box office are important to Microsoft. Microsoft plans to illicit information about movie-making to generate box office hits. My researched analyses from the obtained Microsoft movie data will determine what kinds of movies should be made for Microsoft and how to navigate a gigantic movie industry. Also, my uncovered conclusions can give direction on how to continue to improve the movie-making process.

### Business Problem

Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but the problem is they don’t know anything about creating movies. They have hired me to help them better understand the movie industry. I am charged with exploring three questions about what types of film are currently doing the best at the box office. I must translate these findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what types of film to create.

### The Data

In the folder `zippedData` are movie datasets from:

* Box Office Mojo
* IMDB
* The Numbers

I was given the choice of what data from these datasets to use and how to use it.

### Movie Analysis Methods and Results

Microsoft wants to create movies. 
 
Microsoft might want to know which movie studios are popular for producing movies. A good movie studio choice could help a film succeed. One question Microsoft might ask is:

What studios are popular to collaborate with or investigate based on number of movies they produce?

I looked through a provided movie dataset from the Box Office Mojo website to answer this question for Microsoft. I performed two analyses to answer this question to show two different scales for the analyses. The first analysis determined the number of movies created per studio for the first 20 rows in the provided Box Office Mojo dataset:

![twenty movies studio head](MovieDataImages/moviestudios.png)

Buena Vista(BV), Warner Brothers(WB), and Paramount/DreamWorks(P/DW) studios produced the highest number of movies out of all the movies produced in the first twenty rows of the Box Office Mojo dataset.

The second analysis determined the number of movies created by the top 20 studios ordered by number of movies per studio in the whole Box Office Mojo dataset 

![top twenty studios number](MovieDataImages/moviestudios2.png)

This second analysis shows that IFC Films(IFC), Universal Studios(Uni.), and Warner Brothers Studios(WB) are considered popular because they produced the greatest number of films according to the Box Office Mojo dataset.

Microsoft might want to look at what specific movies in general are extremely popular. A popular movie can provide a lot of information to a filmmaker. Popular movies could have specific traits about them that influence filmmaking such as run time minute totals. Microsoft might ask the question:

What movies got the most votes online and what is a common trait these films share?

Movie datasets provided for this project from The Internet Movie Database(IMDb) can answer this question.

![movies by num votes](MovieDataImages/pinkgraph.png)

After compiling the data from the IMDb datasets, "Inception," "The Dark Knight Rises," and "Interstellar" were the specific movies found to receive the most votes in the IMDb movie datasets.  These movies can be considered most popular in comparison to the whole dataset.

![popular movies by run times](MovieDataImages/poprunmovies.png)

"Inception," "The Dark Knight Rises," and "Interstellar" were popular movies found to produce higher than average run time minutes.

Another aspect of movie creation that Microsoft might want to look into is how a movie production budget and the amount of money the movie makes interrelate. Microsoft might ask:

How does production budget relate to domestic gross for movies?

The answer to this question can be determined using the The Numbers dataset. 

![productionbudget vs domestic gross](MovieDataImages/pbdgmovies2.png)

The scatter plot diagram of production budget and domestic gross displays movies have a fairly relative domestic gross in comparison to production budgets at lower values. Higher production budgets are closer to outlier data with relation to domestic gross. Lower production budgets are less risky.

Side note: My bar graphs included subsets of 20 values as the random number of values to generate a good dispersion of data. This is part of the data cleaning processes.  When too many or too few items are used in a dataset, the dataset may be much more difficult to interpret. My conclusions from the data are generated with cleaned data.

### Conclusions

Here are the findings in response to Microsoft's three questions:

- IFC Films, Universal Studios, Paramount Pictures, and Warner Brothers Studios created the most films in the Box Office Mojo dataset. They are popular studios to use or collaborate with for movie making.

- According to IMDb datasets, "Inception," "The Dark Knight Rises," and "Interstellar" are the movies that received the most number of votes at IMDb.  They are great movies to watch for movie-making purposes based on their popularity. Also, they have higher than average run time minutes. Microsoft should make a movie with a longer run time because it could be more popular.

- The Numbers movie dataset displays a fairly regular relationship between production budget and domestic gross at lower values. Higher budget movies in the dataset might be considered outliers and did not necessarily produce higher domestic gross. Microsoft should make a movie with a lower production budget because there is less monetary risk involved.

### Recommendations for Further Analysis

- A comparison could be made between production budget and worldwide gross from The Numbers movie dataset.  My analysis only covered the production budget and domestic gross relationship for movies within The Numbers movie dataset. 

- Some analyses on movies based on the year they were released might add more dimensions to my results. The history of a specific year can influence the movies that were released, how they were released, and why they were released.

- The relationship between movies and genre popularity could be looked at. Certain movie genres may be more popular to use when creating a feature film.

### For More Information

- See the full analysis of my findings in MovieDataAnalysis.ipynb

- Contact me at jmstipanowich@gmail.com

### Repository Structure

├── MovieDataImages

├── zippedData

├── MicrosoftMovieDataPowerpoint2.pdf

├── MovieDataAnalysis.ipynb

├── README.md

├── student.ipynb