# project-01

Project 1 repo for STA/ISS 313 - Spring 2023.

### Data Dictionary
The original data dictionary is taken from TidyTuesday's dictionaries for the original `details.csv` and `ratings.csv` files and modified to match our combined dataset. 

# `comprehensive.csv`

|variable      |class     |description |
|:-------------|:---------|:-----------|
|id            |double    | Game ID (BoardGameGeek classifier) |
|primary       |character | Game name |
|description   |character | Description of game |
|yearpublished |double    | Original publication year |
|minplayers              |double    | Min n of players|
|maxplayers              |double    | Max n of players |
|playingtime             |double    | Playing time in minutes |
|minplaytime             |double    | Min play time |
|maxplaytime             |double    | Max plat tome |
|minage                  |double    | minimum age|
|boardgamecategory       |character | Category |
|boardgamemechanic       |character | Mechanic   |
|boardgamefamily         |character | Board game family   |
|boardgameexpansion      |character | Expansion |
|boardgameimplementation |character | Implementation  |
|boardgamedesigner       |character | Designer |
|boardgameartist         |character | Artist  |
|boardgamepublisher      |character | Publisher     |
|owned                   |double    | Num owned  |
|trading                 |double    | Num trading  |
|wanting                 |double    | Num wanting |
|wishing                 |double    | Num wishing |
|rank          |double    | Game rank on BGG |
|average       |double    | Average rating  |
|bayes_average |double    | Bayes average rating|
|users_rated   |double    | Users rated |
|url           |character | Game url |
|thumbnail     |character | Game thumbnail  |
