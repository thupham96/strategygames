# Mobile Strategy Games
## by Thu Pham


## Dataset

> The mobile games industry is worth billion of dollars, with companies spending vast amounts of money on the development and marketing of these games to an equally large market.
> The dataset includes 17007 strategy games on the Apple App Store. It was collected on the 3rd of August 2019, using the iTunes API and the App Store sitemap. The data used in this project was downloaded from Kaggle.
> Using Python and its libraries, I will gather data, assess its quality and tidiness, then clean it. Then, I will use the number of ratings as a proxy indicator for the overall success of a game, and then work out what factors make a successful game by using univariate, bivariate and multivariate exploration.


## Summary of Findings

> Univariate Exploration:
- There are 21 primary genres. The most popular genres are Games (95.76%), Education (1.31%), and Entertainment (1.16%). The least popular genres are Shopping (0.006%), Travel (0.006%), and Medical(0.012%).
- The average user rating ranges from 0 to 5.0. The majority of them is 4.5.
- As the price increases, the number of apps decreases. 82.39% of the apps is free. 14.63% is low. 1.59% is medium. 0.22% is high.
- There are 4 age ratings: 4+, 9+, 12+, and 17+. 69.4% is 4+. 14.6% is 9+. 12.1% is 12+. 3.9% is 17+. As the age rating increases, the number of apps decreases.
- The most popular game genres are strategy (42.31%), entertainment (15.76%), and puzzle (9.06%).
- The most common developer is Tapps Tecnologia da Informa\xe7\xe3o Ltda. with 123 apps.

> Bivariate Exploration:
- The genres that have the highest average user ratings are Food & Drink (4.63), News (4.57), and Music (4.50).
- Age rating 4+ has the highest average user rating (4.33). Age rating 12+ has the lowest average user rating (4.25). All 4 age ratings have similar average user ratings, and there is not much difference among them.
- The high price category has the highest average user rating (4.31), and the low category has the lowest average user rating (4.28). The average user ratings of all price categories are quite similar, and there does not seem to be a correlation between price and average user rating.
- For the apps that have primary genre as Games, Magazines & Newspapers has the highest average user rating (5.00), and Books has the lowest average user rating (4.00).
- In all genres except for Book and Music, age 4+ holds the highest proportion.
- There is little negative relationship between size and average user rating.
- The average size of apps tends to increase over time. There are a few times where there were spikes in average size. The highest one is in 2014 where the average increases to more than 3.5x(10^9) bytes.

> Multivariate Exploration:
- For each of the top 10 genres, there does not seem to be a correlation between age rating and average user rating.
- For all age ratings, the average user ratings for price categories are higher than 4.0, except high price category - age rating 12+. There does not seem to be a correlation between price category and average user rating for all age ratings.
