# Project 1- Movies exploration

**Author**: Milena Afeworki

## Overview

This project analyzes theatrical films with intention of guiding Microsoft through the launch of its new film studio. The results of these analysis will yield actionable insights that Microsoft's new studio head can use to determine what types of films to develop.

## Business Problem

Microsoft is planning to take part in the movie industry and is looking for recommendations on what movies do best at the box office. They will use this information to make informed decisions on starting a new movie studio and having actionable insights on past movie performance to help decide what types of films to create. This analysis will review data provided from IMDb and Box Office Mojo to create recommendations that Microsoft can use in their new business experience. 

## Data

The analysis shown are based on the datasets in the folder ```zippedData``` gathered from the following websites

    * https://www.boxofficemojo.com/ (Box Office Mojo)
    * https://www.imdb.com/          (IMDB)
    * https://www.themoviedb.org/    (TheMoviesDB)
    * https://www.the-numbers.com/   (The Numbers)

## Methods

The methodical explorations and analysis done for this project is mostly centred around descriptive statistics calculated from the data provided. These metrics were useful in identifying popular genres, Directors and writers involved for highest profit, and the ideal level of budget investment towards film making.

## Results

After a rigorous investigation on the data to see what effect these data points have on revenue, the observation was that the type of Genres had an important role on the likelyhood of where most profit would come from.  After exploring the relationship between genre and revenue to see which genre would have the greatest chance of return on investment the analysis showed that Crime movies have the greatest returns.


![image.png](attachment:image.png)

Next was to investigate who were the directors and writers engaged in the making of these genres for the most returns. So we discover the Gross profit of the top 3 genres with the following crew to be as follows.

![image.png](attachment:image.png)

Last but not least, assumably production budget would have a significant impact on the overall financial return of a movie in the market. To support this hypothesis and back it up with some facts of figures, here we would be looking more into the relationship of the Budget and Revenue to provide an ideal range of Budget for Microsoft to get started on.

![image.png](attachment:image.png)

## Final Recommendations

* Focus more on producing films of genre 'Crime', 'Action', and 'SciFi'.
* Creating more opportunities to engage the following writers and directors:
   - Rick Jaffa
   - Amanda Silver
   - Stephen McFeely
   - Christopher Markus
   - Anthony Russo
   - Joe Russo
   - Derek Connolly
   - Colin Trevorrow
   - Stan Lee
   - Jack Kirby
* Reserve a budget of 55,000,000 - 150,000,000 in order to compete with
  some of the highest earning production companies.

## Further Research

* Getting insights on how metrics like "popularity" and "rating" would   potentially affect the amount of time a customer would spend within a streaming of a movie watching platform, that way aside from the financial gain Microsoft could guarantee keeping loyal customers.

* Explore the times of year movies are released and look out for any correlation on when they usually have their peak returns on. 

## Repository Structure

├── notebooks
├── data
├── images
├── README.md
└── Movie_data_exploration.ipynb
