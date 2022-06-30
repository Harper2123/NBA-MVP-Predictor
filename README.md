# NBA-MVP-Predictor
Exploratory Data Analysis on NBA data from 1991-2022 to predict MVP for a year
The Primary source of data for this project is :- https://www.basketball-reference.com/
The project contains the following files:-
1) mvp folder:- It contains html pages of the MVP rankings from 1991-2022
2) player folder:- It contains html pages for each year from 1991-2022 containing the data of every player from these years.
3) team folder:- It contains html pages for each year from 1991-2022 containing the records of every team for these years.
4) mvps.csv:- This csv file contains the usable data which is scraped from the HTML pages of the mvp folder.
5) players.csv:- This csv file contains the usable data which is scraped from the HTML pages of the player folder.
6) teams.csv:- This csv file contains the usable data which is scraped from the HTML pages of the teams folder.
7) nicknames.csv:- This csv file contains the Team names with the abbreviations generally used for them.
8) player_mvp_stats.csv:- This csv file contains the data of players.csv, teams.csv and mvps.csv
9) msedgedriver:- It was used to automate MS Edge for the purpose of data collection. The application may change if different browser is used.
10) web_scraping.ipynb:- This notebook is the first notebook of the project. In this notebook, we are downloading the html pages, extracting the required data, and then saving it into their respective folder. Then we use that data to make Pandas dataframe, and then convert it into csv file.
11) data_cleaning.ipynb:- This notebook is the second notebook of the project. In this notebook, we clean our data and then perform some analysis on the data specially looking at the correlation of different attributes with "Share".
12) model.ipynb:- It is the last notebook of the project. In this notebook, we split the data for training and testing purpose, and tried two different models for better accuracy.
