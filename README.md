# DATASCI_VGSwithRatings
Final Project for DATASCI using "Video Game Sales with Ratings" Dataset

## Dataset
The dataset is “Video Game Sales with Ratings” by Rush Kirubi, from Kaggle. The dataset contains the following: the name of the game, the platform the game is released on, the year the game is released, the genre of the game, the publisher of the game, how many millions of units were sold in North America, Europe, Japan, and other regions, as well as the aggregate of the global sales, the MetaCritic score, how many critics, the User score, how many users played the game, the developer of the game, and the ESRB rating of the game. For this analysis, only the name of the game, the genre of the game, the platform where the game is published on, the global sales, the breakdown of those sales, and the critic score will be used.

## Now why this dataset? 
Because this dataset contains data that can be used to measure the success of publishers. 

## What did we want to know? 
How do the critic scores affect the sales?
We wanted to know if the intuitive relationship holds.
How does the number of platforms the publisher publishes on affect their sales?
We wanted to know if games are played on more platforms, will the sales be higher?
How does the number of titles the publisher publishes affect their sales?
We wanted to know if publishers have more games under their belt, will the sales be higher?
What is the best selling Platform in each Region?
We simply want to know which is the best selling platform in each region.
What is the best selling Genre in each Region?
We simply want to know which is the best selling genre in each region.

## What we found out!
After looking through the data, we found out that NA and EU contain the largest share of the video game market. It is seen in the data that NA and EU have the majority of the market sales. We think this is due to the fact that NA and EU are a whole lot larger compared to the other regions.

The next thing that we wanted to find out is the number of platforms the publisher published on will affect the sales. The data showed that the more platforms used, the higher the sales of the publisher will be. This is due to the fact that the same game is available on multiple platforms.

Furthermore we also wanted to know if the number of titles published will affect sales. Based on the data it is heavily seen that the more number of titles published the higher the sales will be and the lower the number of titles, the less sales the publisher will have. This is due to the fact that the more titles means the more chances of having a successful game thus, resulting in more sales.

To boost our understanding, we included the relationship between the number of platforms published on and the number of titles published. We found that the relationship is exponential. This is because games are published on many platforms.

If we were to put ourselves in the shoes of a developer, we’d want to find out what is the best selling platform and genre in each region. We found out that For North America, the X360 has the most sales. For Europe and the other regions, the PS2 has the most sales. For Japan, the DS has the most sales. As for the genres, For North America, Europe, and the other regions, action games sell the most. While, for Japan, the RPGs sell the most.

## Application of the gained knowledge
To apply what we’ve learnt, we trained a linear regression model on the data. According to our model, a hypothetical publisher that published on 10 platforms and published 10 titles will sell 9.6 million units globally.

## Conclusion
We conclude that not the global sales does not solely depend on the critic score. It still depends on the accessibility of the game depending on the platforms or region that they've encompassed. People should not be persuaded by the MetaCritic score of the game, they should play the game because they're interested in or love to play that kind of game.
