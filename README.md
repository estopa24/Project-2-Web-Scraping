# Web-Scraping Project

This project's purpose is to find 5 webpages and ask several questions of the data in each webpage that will be answered through the use of web scraping and data analysis. Data is scraped from these webpages (the webpages' html data is requested), and it is parsed by using Beautiful Soup. Specific tables that will be used to answer the questions are then extracted from the parsed data and read into python as pandas dataframes. These dataframes are then cleaned in order to make them more readable, organized and concise to more easily find the specific data needed to answer the questions. The questions are answered in markdown cells. Markdown cells are also used throughout the notebook code to explain each step of the code. The answers for two of the 4-5 questions asked are represented through the use of graphs that were created through both seaborn and matplotlib.

The questions that were given to be answered included:
1. How much more playing time did the player with the highest playing time have in Real Madrid than in Paris Saint Germain?
2. Which player made the most goals in the 2023-2024 season in Real Madrid and in Paris Saint Germain?
3. What are the names and number of matches played of the players with the top 10 most matched played in the 2023-2024 season in Real Madrid?
4. What are the names and ages of the top 10 players listed in the 2023-2024 standard stats of Paris Saint Germain?
5. How many players of each nationality are in the 2023-2024 Real Madrid and Paris Saint Germain teams?

The answers to these questions are in the attached Jupyter Notebook file. 

The url's that were scraped in this project were:
1. https://fbref.com/en/squads/53a2f082/Real-Madrid-Stats
2. https://fbref.com/en/squads/e2d8892c/Paris-Saint-Germain-Stats
