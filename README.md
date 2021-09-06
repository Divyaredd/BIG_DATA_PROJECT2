## An Analysis on RAWG API

by Divya

## Project Description

An analysis on RAWG API.

RAWG is the largest Video Game Database and game discovery service with 500,000+ games data.

## TECH STACK

1.Pyspark [3.1.2]

2.Spark [3.1.2]

3.Spark SQL

4.Pandas [1.3.1]

5.Python [3.8]

6.Git/GitHub 


# Data Summary

**Content

Each row contains information about one game. There are several columns that have multiple values like platforms, genres, … In those cases, values are separated by double pipes ||.

Column definitions:

id: An unique ID identifying this Game in RAWG Database
slug: An unique slug identifying this Game in RAWG Database
name: Name of the game
metacritic: Rating of the game on Metacritic
released: The date the game was released
tba: To be announced state
updated: The date the game was last updated
website: Game Website
rating: Rating rated by RAWG user
rating_top: Maximum rating
playtime: Hours needed to complete the game
achievements_count: Number of achievements in game
ratings_count: Number of RAWG users who rated the game
suggestions_count: Number of RAWG users who suggested the game
game_series_count: Number of games in the series
reviews_count: Number of RAWG users who reviewed the game
platforms: Platforms game was released on. Separated by ||
developers: Game developers. Separated by ||
genres: Game genres. Separated by ||
publishers: Game publishers. Separated by ||
esrb_rating: ESRB ratings
added_status_yet: Number of RAWG users had the game as "Not played"
added_status_owned: Number of RAWG users had the game as "Owned"
added_status_beaten: Number of RAWG users had the game as "Completed"
added_status_toplay: Number of RAWG users had the game as "To play"
added_status_dropped: Number of RAWG users had the game as "Played but not beaten"
added_status_playing: Number of RAWG users had the game as "Playing"




## Problem Statements

1.Which is the top most rated games accross all platform.

2.Which game developer has released the most number of games.

3.Which game genres has most games.

4.Number of games released per year

5.Games with longest updation time






## Data set used

#RAWG Data Set API


## Data Definations

 For all problems we used RAWG games dataset

eg: 1,dgeneration-hd,D/Generation HD,,2015-10-23,False,2019-09-17T11:58:57,
http://dgeneration.net,0.0,0,1,80,2,292,0,4,PC||macOS||Xbox One||PlayStation 4||Nintendo Switch,
West Coast Software,Adventure||Puzzle,West Coast Software,Everyone 10+,4,88,2,2,0,0



