## Global Suicide Rate Analysis


Suicide is a global major national health problem. According to WHO, more than 700,000 people die due to suicide every year, and for every suicide attempt, there are many more people who attempt suicide. It's also stated that suicide is the fourth leading cause of death among 15 - 19-year-olds worldwide and the leading cause of death in the USA. 

However, my report is an exploratory/descriptive analysis of the case study. which is aimed to identify an analysis of suicide rates among countries around the world. In this study, I showed that the global suicide rate by male gender is higher than the female gender, and by continent, Asia appears to be associated with an increased risk of 2.7M by population, while Africa is linked with the least suicide rate.

**Enjoy the Read!**

## Table of Contents

1.   Introduction
2.  Data Wrangling
3.  Exploratory Data Analysis
4.  Conclusion
5.  Reference

# Introduction 
This project is on Global Suicide Rate Insight Analysis, provided by Side Hustle Nigeria. 
The analysis was restricted to 101 countries for which the suicide number and age group were available from 1985 to 2016. 
The specifics featured in this report are;
1.   Suicides by country 
2.  Suicides by sex
3.  Suicides by age groups including "5-14",
"15-24", "25-34", "35-54", "55-74", "76+".
4. Suicides by year: from 1985 to 2016
5. Number of Suicides 
5. Suicides by continent
6. By GDP per capita
7.  By population
8. Suicides per 100k population


# Data Wrangling

The dataset was downloaded from kaggle.com. The data was prepared and analyzed with Microsoft Excel and Power Bi tools. 

  **A continent column was created using [ =IF(A10=",",INDEX(Location!$A$2:$A102,MATCH(A10,Location!$B$2:$B$102,1))) ]**
 
Also, new columns were created using the DAX function

![suicide rate dax formular.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1657479319767/oCzpeXtif.png align="center")


![average gdp dax formula.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1657479502064/UxiKn2ujY.png align="center")

# Exploratory Data Analysis

### Analysis 1 ( Suicides number by country)

This analysis shows that, among all countries, Russia had the highest suicide rate of 1.2M population from the year 1984-2016, followed by the united kingdom with a suicide number of about 1.0 M.

![Capture 2.PNG](https://cdn.hashnode.com/res/hashnode/image/upload/v1657467366380/vTQGnHmSH.PNG align="center")

### Analysis 2 ( Suicides Number by Sex )

This analysis shows that the male gender is linked with the highest rate of about 76.89% of suicides number by population.

![Capture 3.PNG](https://cdn.hashnode.com/res/hashnode/image/upload/v1657467445307/q2mjrgBag.PNG align="center")

### Analysis 3 ( Suicides Number by Age Group)

This analysis shows that the age group of 35-54 years had the highest suicide number of about 2.5M population and the age group of 5-14 years had the least suicide number of 0.1M.

![Capture 4.PNG](https://cdn.hashnode.com/res/hashnode/image/upload/v1657467511463/XHHjx-Stt.PNG align="center")

### Analysis 4 ( Suicides Number by Year)

This analysis shows the rate of suicides number from the year 1984- 2016 for all countries. the year 1999 appears to have the highest suicide rate with 256,119 suicides recorded.

![Capture 1.PNG](https://cdn.hashnode.com/res/hashnode/image/upload/v1657467220605/GHP_1toro.PNG align="center")


### Analysis 5 ( Suicides Number by Continent)

This analysis shows that Asia records the highest suicide number, with Africa appearing the least on the chart.

![Capture.PNG](https://cdn.hashnode.com/res/hashnode/image/upload/v1657467128335/bmBla8Kr2.PNG align="center")


### Analysis 6 ( Suicides Number by GDP per Capita)

This analysis shows the different averages of GDP per Capital of all countries under review from the year 1984-2016 with their fluctuation in the number of suicides.

![Capture 5.PNG](https://cdn.hashnode.com/res/hashnode/image/upload/v1657467647306/0KuoZQQfg.PNG align="center")

![Capture 6.PNG](https://cdn.hashnode.com/res/hashnode/image/upload/v1657467728153/cnMogQquN.PNG align="center")

### Analysis 7 ( Suicides Number by Population)

Analysis 7 shows that the number of suicide by the population of all countries (101) was 7M population, and it also shows the suicides number of the average population of all countries under review from 1984-2016.

### Analysis 8 ( Suicides Number by 100k Population)

This analysis shows the average of suicides per 100k population from the year 1984-2016, as shown on the dashboard.

# Dashboard Presentation



![sucide dashboard.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1658160925876/s4WX_Ieu0.png align="left")

# Conclusion
The suicides rank differ significantly amongst countries with different GDP per Capital levels from the year 1985-2016. The male gender is associated with an increased risk of suicide as the percentage of suicidal male individuals appeared as 76.89% against females with 23.11%.
It is also important to note that the suicide rate had a progressive increase in Asia countries and zero rates in African countries with the age group (35-54) with the highest population of suicide rate and age group (5-14) with the least.

Evidently, suicide doesn't only occur in high-income countries, but is a global phenomenon in all regions of the world. This might be argued due to the low rate in African countries, but it is important to note that, globally, the availability and quality of data on suicide and suicide attempts are poor. Only 80 member States have good-quality vital registration data that can be used directly to estimate suicide rates. - WHO.

# Reference

Kaggle.com

google.com