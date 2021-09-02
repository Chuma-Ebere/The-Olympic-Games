# The-Olympic-Games
This work was done to analyse the trends in the olympic games. The dataset obtained from Kaggle contains data on all the Games held from Athens 1896 to Rio 2016.
![olympics 1](https://user-images.githubusercontent.com/87578606/131578678-69b4948f-7511-4141-9827-9e5b70b72b09.jpg)


# Olympic Dataset
This is a historical dataset on the modern Olympic Games, including all the Games from Athens 1896 to Rio 2016.
Some of the rows contained in the dataset include; 'Name',	'Sex',	'Age',	'Height',	'Weight', 'region', 'Year', 'Season', 'Sport', and 'Medal'.
Data Source [Kaggle] (https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results)
You will find that there are two datasets, one I have named 'athlete' and the other 'regions'.

# Learning Points
This dataset gave me a taste of data cleaning to start with.
I made use of the Numpy, Pandas, Seaborn, and Matplotlib Python libraries.

# Steps
1. Explored the datasets to understand their components.
2. Merged the two datasets on their primary key named 'NOC' and named the new table 'olympics'.
3. Description of the new dataset using the 'describe' function.
4. Replaced the missing values of Age, Height and Weight with their average as determined in step 3.
5. Examined the components of each column using the 'value_count' function.
6. Dropped the columns 'notes', 'Team' and 'Games' which I found to be unnecessary.
7. Analysed the new dataset to determine the trends in the olympic games. The various analysis are listed below.

# Analysed country trends to determine;
  * Top and least performing countries in the history of the olympics games.
  * Which countries send the most athletes?
  * Trends in the medals won by each country over time.

# Results from analysing the age distribution among the athletes
  * Most of the athletes to have ever taken part in the olympic games were between 20 and 30 years old.

![olympics 3](https://user-images.githubusercontent.com/87578606/131578753-0db1e0db-5590-4915-a21e-750e69e4ec16.png)
# Results from analysing the summer and winter olympic games
  * A total of 17 games were held during the winter olympics.
  * Over 50 games were organised during the summer olumpics.

# Results from analysing the gender distribution at the olympics
  * 72.5% of the all athletes since the inception of the olympic games are male.
  * The year 1992 summer games recorded the highest number of male contestants, which was 8853.
  * For both the winter and summer games, the number of females at the games increased yearly. 
  * Year 2016 recorded the most number of female contestants at the games, exceeding 6200 females.

![olympics 2](https://user-images.githubusercontent.com/87578606/131578797-b60c36ff-9701-4965-a143-9a03d4faf657.jpg)
# The results from analysing the medal winners over time showed the following:
  * The same set of countries have maintained the top 10 spots in medal wins through the year.
  * The United States consitently tops all medal categories, with Russia and Germany taking the next 2 spots.
  * Four competitions at the olympics namely, Arts, Roque, Archery and Shooting, have all had gold medal winners who were over 60yrs of Age.
  * Three Archers over 60yrs old from the United States have won gold medals.

# Results from analysing the most recent olympic games (2016)
  * The united States tops the medal ranking table, clinching a total of 139 gold medals.
  * The UK, Russia and Germany are next on the medal ranking table with each winning a total of 64, 52 and 49 gold medals respectively.

# Finally, the results from analysing the height and weight composition for all male and female olympic contestants in history
  * Most of the female athletes in history weighed below 75kg and were not more than 175cm tall.
  * However, the reverse is the case for male athletes as majority of the male athletes to have ever competed were over 75kg in weight and 175cm in height.
  * The heaviest male to have ever competed was just over 220kg in weight while the heaviest female was about 170kg.
  * The tallest male to have ever competed was over 225cm and the tallest female was around 210cm.
