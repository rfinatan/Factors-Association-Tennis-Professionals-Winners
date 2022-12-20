# Factors-Association-Tennis-Professionals-Winners

Of all the major competitive sporting events occurring on an annual basis, tennis is arguable one of the best suited for advanced analytical analysis due to its large amount of data generated on a per-match basis. To better understand the factors involved in what determines a winner in a given tennis match, chronological data across a vast recorded match history is required. 

This study aims to identify the highest-contributing attributes of an Association of Tennis Professionals (ATP) winner’s performance for the years 2000 to 2022. The study is aimed at tennis fans and sports betting enthusiasts looking to gain an understanding of a player’s performance from a list of hundreds of ATP-registered players. 

In addition to standard match data available via public repositories, the study will attempt to engineer features for modelling pertaining to player matchups, environmental scenarios, and tournament-specific performance.

The data will be modelled and evaluated using several random forests algorithms. Baseline accuracy will be established by a default random forest, accompanied by a grid-search optimized random forest, and a rangerTuner optimized random forest. Lastly, the models will be evaluated against one another for model-specific accuracy and match-up winners’ probabilities will be recorded to display model confidence in a winner’s prediction.

The data under study consists of 22 comma-separated value files tracking ATP-level tennis matches on an annual basis sourced by Jeff Sackmann. 

The files contain information about ATP players, including their IDs, names, hand preference, birth dates, country of origin, and height. Ranking information is also included, with data available from 2000 to the present. Results and statistics for ATP matches are included in separate files for each season, covering tour-level main draw matches, tour-level qualifying and challenger main-draw matches, and futures matches. These files contain biographical information and ranking data for each player, as well as age and ranking points as of the start of the event. MatchStats, which provide detailed statistics about the matches, are available for tour-level matches from 2000 to 2022, for challengers from 2008 to the 2022, and for tour-level qualifying matches from 2011 to 2022. Some tour-level matches may be missing statistics due to unavailability from ATP. Davis Cup matches are included in the tour-level files, but do not have MatchStats available until recent seasons. 
