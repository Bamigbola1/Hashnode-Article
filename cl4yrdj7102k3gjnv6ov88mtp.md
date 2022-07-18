## Football World cup Data Analysis from 1930 till date


# Overview

My task this week is quite an interesting one, I was tasked with analyzing Football World Cup using data from 1930 till the present by Power BI. I worked on this project and successfully delivered all required research points/questions. In this report, I have documented the project context, our analysis process, findings, and presented the research points on two dashboards.
 

**Enjoy the read!**

## Table of Content
1.	Introduction 
2.	Data Wrangling
3.	Exploratory Data Analysis
4.	Conclusion





# Introduction 

## Context
The FIFA World Cup, often simply called the World Cup, is an international association football competition contested by the senior men's national teams of the members of the Fédération Internationale de Football Association (FIFA), the sport's global governing body. The championship has been awarded every four years since the inaugural tournament in 1930, except in 1942 and 1946 when it was not held because of the Second World War.

The World Cup is the most prestigious association football tournament in the world, as well as the most widely viewed and followed single sporting event in the world. The cumulative viewership of all matches of the 2006 World Cup was estimated to be 26.29 billion with an estimated 715.1 million people watching the final match, a ninth of the entire population of the planet.

17 countries have hosted the World Cup. Brazil, France, Italy, Germany, and Mexico have each hosted twice, while Uruguay, Switzerland, Sweden, Chile, England, Argentina, Spain, the United States, Japan, and South Korea (jointly), South Africa, and Russia have each hosted once. Qatar will host the 2022 tournament, and 2026 will be jointly hosted by Canada, the United States, and Mexico, which I give Mexico the distinction of being the first country to host games in three World Cups. 

## Content
The Football World Cup Dataset shows all information about all the world cups in history and records all previous Football World Cups from 1930 to 2018. The dataset is downloaded from Kaggle.com
### Research Questions; 
1.	Number of world cup winning titles.
2.	Attendance, Number of teams, Goals, and Matches per Cup.
3.	Goals Per Team Per World Cup.
4.	Matches With the Highest Number of Attendance.
5.	Stadium with the Highest Average Attendance.
6.	Which Country had Won the Cup?
7.	Number of goals per Country.
8.	Match outcome by home and away teams.


## Data Wrangling
This step involves loading the dataset, cleaning, and trimming the dataset.
![Data Cleaning( Find and replace).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1656209882576/EAowkY00v.png align="left")


**General Properties**

![data cleaning 3.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1656210455012/0NWUZrnm6.png align="left")

![data cleaning.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1656210478708/F4ApQ2XaK.png align="left")

### Data Cleaning
Here, we first checked for number of null and missing values present in each row, after determining and fixing the null and missing values, we then dropped them and observed the dataset for other null values. 

![maindataset.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1656210240863/KOPN2UZRm.png align="left")

![data cleannng 4.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1656210504648/WdDMExfvW.png align="left")



![sample data 2.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1656210268452/1emE5d-SB.png align="left")


# Exploratory Data Analysis
### Research Question 1 (Number of world cup winning titles)

Fig 1 shows that Brazil tops the Cup winning list, with 5 titles won, followed by Italy and Germany with 4 titles each.

![country won.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1658146344361/7BnlXo37o.png align="left")
Fig 1: Number of World Cup Won by Country

### Research Question 2 (Goals Per Team Per World Cup)

![goal per country.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1658146385565/LpYKYpvPu.png align="left")
 Fig 2: Goals Per Team Per World Cup


### Research Question 3 (Matches With the Highest Number of Attendance)

![new attendance.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1658146428113/0b6lYtKZG.png align="left")
Fig 3: Matches with Highest Attendance



![match palyed by cup.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1658146476264/D6joQDOZ6.png align="left")
Fig 4: Matches Played Per Cup

 ### Research Question 4 (Stadium with the Highest Average Attendance)
In Fig 5,   Maracana Stadium located in Rio de Janeiro in Brazil records the highest average attendance. The current capacity of the Stadium is 78,823 but had previously seen on more than 26 occasions over 150,000 spectators before the current renovation.

![new highest.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1658146523045/m0gghsaZ2.png align="left")
Fig 5: Stadium with the Highest Average Attendance

### Research Question 5 (Which Country had Won the Cup?)


![winning country by tournament.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1658146571388/6LXS9LjV3.png align="left")
Fig 6. Winning team by Year


### Research Question 6 (Number of goals per Country)


![goal scored per country.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1658146612015/-Sw8-rNIj.png align="left")

Fig 7: Number of Goals scored  Per Country

### Research Question 7 (Match outcome by home and away teams)


![ouitcome of home and away.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1658146644203/854_DiwIX.png align="left")
Fig: Match Outcome by Home and Away Teams

# Dashboard Presentation

![startscreen.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1658146665677/ELqJHjWLq.png align="left")

![worldup 1.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1658146702238/K0Ou4ecc0.png align="left")

![wolrdcup 2.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1658146722892/sOtS7SbrS.png align="left")



# Conclusion
From our analysis, we found that the World Cup was founded 92years ago, and since then, 21 tournaments have been hosted by 17 countries. 

From Fig 1, we saw that Brazil is the most successful World Cup Team with a total of 5 titles Won, and they are the only team to have played in all 21 tournaments. 

The research also found that a total of 41,508,418 attendance have been recorded across all tournaments. Also, a total of 79 teams have been recorded to have featured in the World Cup.

Finally, the analysis shows that a total of 1800 games have been played with a total goal of 2,548 goals scored in all tournaments. 

 



# References
Kaggle.com


https://en.wikipedia.org/wiki/FIFA_World_Cup

