# MarchMadness
The webscraper is a work in progress.  It can be adapted to download the stat differentials for each team, each week, in the nation.  But thats a big webscrape, so I set it up to go after only the teams in the 2019 MarchMadness tourney.  I didn't automate it for the entire tournament, but instead each of the four regions need to be run independetly. The resulting files are a dataframe with the average stat differentials for each of the 16 teams in the region. 
These are written to disk and then opened in the model building .Rmd file, where the files can be altered interactively to predict different scenarios throughout the tournament.
For each game the location has to be set manually. 
