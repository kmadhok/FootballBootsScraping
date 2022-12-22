# FootballBootsScraping

## General

This repository has code that was developed to scrape footballdb.com to get the brands of the shoes that players wore in the 2022 World Cup. I predominantly used Beautiful Soup and Requests. 

## First Step

The first step was to scrape the shoe data from footballbootsdb after this I stored the player and brand in a pandas dataframe. 
To do this I went through the website and collected the specific tags I wanted to reference when scraping the website. After that I put all of these tags I wanted to explore into a function in which I use to scrape the brand and player information. After that I simply collect the scraped data in an empty list which is appended into an empty dataframe. 

## Second Step

The second step was to scrape the team links from footballbootsdb. This step is important because the previous funciton in step one needs a url as an input to scrape footballbootsdb. By scraping all of the team links we can store them in a list which can later be used to call all of the players and brands in once call. 

## Third Step

The third step is to call all of the players and brands through the function we created in the first part and input the urls we collected in our list in the second part. After this we combined this dataset with statisitcs from the world cup to get a complete picture of both brand and performance for each player. 

## Fourth Step

The fourth step after having our finished csv is to analyze it and see if there are any trends. This step of analysis was done in Tableau as it also allowed us to have different visualizations. 

## Resources

Scraped: https://www.footballbootsdb.com/

Player Statistics: https://www.kaggle.com/datasets/swaptr/fifa-world-cup-2022-player-data
