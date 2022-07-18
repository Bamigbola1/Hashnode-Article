## Covid 19 disease  Live Data insight Analysis

# Overview
This week, I have been tasked to carry out an analysis on Covid-19 disease. With less than a week to work and with much difficulty in dataset access, I was able to give insights into the available dataset and visualize our analysis. The analysis gives insight into the covid-19 disease in different continents and countries of the world. 

### Table of Content

- Introduction
-   Data Scrapping
-   Data Wrangling
-   Data Modeling
-   Data Visualization 
-   Conclusion
-   Limitation

# Introduction
 The dataset used is live data and it clearly revealed some of the analysis points below. The dataset includes the Countries, Total Cases, New Cases, Total 
Deaths, New Deaths, Total recovered, New recovered, Active Cases, Serious Cases 
among others.
The research points that were given to be used for this analysis are as follows;
1. Infected Demographic by Sex
2. Infected Demographic by age range
3. Reported cases by date
4. Affected locations heatmap
5. Mortality by type
6. Mortality by region
7. Mortality by sex
8. Mortality by age range
9. Mortality rate
10. Total death

Steps such as cleaning, analyzing, and visualization were done using Microsoft Power BI.

# Data Scrapping  
The data was gotten from http://www.worldmeters.info/coronavirus/. This site updates the dataset from time to time, every day. 

# Data Wrangling
The dataset was extracted, cleaned, and trimmed.

DATA CLEANING
- The numerical columns were changed from text form to the whole number.
- Replacement of blank cell as well as N/A with zeros.
- Removal of world cell from the dataset
- The totals at the end of each column were filtered out.
- Some additional columns like herd immunity, Recovery Rate, and Recovery Prospect, were generated using the DAX language to help give better insights into the research.


![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1655657258725/wQWl2j7vH.png align="left")

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1655657283752/Q898fkH0-.png align="left")

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1655657307818/lGqP5_pBu.png align="left")
 
# Data Modeling




![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1655656726429/dtDLCDzZl.png align="left")

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1655656782545/c_OkZtJXt.png align="left")

# Data Visualization
###  Analysis 1 (Total cases and Total Recovered)

![total cases and total recovered.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1658158006247/kDqJSgNEs.png align="left")
In Analysis 1, I investigated total cases and total recovered. My analysis shows that USA has the highest recorded cases with a high recovery. Also, the analysis shows a good recovery rate across the countries. 

 
### Analysis 2 ( Total Death by Country)

![total death by country new.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1658158052549/wmoSl7gt4.png align="left")
In Analysis 2. We visualized total death by Country, and the result has USA, Brazil, and India, recording the top 3 highest death.

### Analysis 3 (New Deaths and  New  Cases by Country)


![new death new case.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1658158076670/KRtfL9_x5.png align="left")

### Analysis 4 (Affected locations heatmap by Country)

![active case by country.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1658159816121/C656hbM9r.png align="left")
The map here shows active cases by country in real-time. 

### Dashboard


![covid dashboard.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1658159848745/Q5pT-wsYX.png align="left")

# Conclusion

The overall analysis shows a total death of 6M, total recorded cases of 544M, Total recovered of 512M, and total active cases of 15M. 

Finally, I found that, across the countries, there is a good recovery rate of an average of over 90%.  

# Limitation
Getting a dataset that includes all the parameters I needed to analyze the 
analysis points I  was given was quite a challenge... Hence, I settled for the 
best one available. 
 