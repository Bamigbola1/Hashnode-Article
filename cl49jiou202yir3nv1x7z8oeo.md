## My First Data Analytics  Team Project on Knorr

### Overview
The past few months in the side hustle internship have indeed been an exciting journey in the world of data. After successful completion of the program, I enrolled in a six weeks boot camp program with Side Hustle to probe further into data analytics by examining real-life data. I am excited to share my first project on investigating an E-commerce website dataset.

Each project will be documented weekly so stay tuned to this space.

### Project: Investigation of an Ecommerce dataset (Case Study: Knorr)

** Table of Contents**

Introduction

Data Scraping

Data wrangling

Exploratory Data analysis

Conclusion

** Introduction**

This analysis is based on a product in Nigeria or used by Nigerians to investigate product sales and draw insights.

** Data Scraping**

This dataset was downloaded from kaggle.com, it contains information about over 2000 entries collected from different stores in the e-commerce Database located in the Southwest region of Nigeria. The dataset includes Order ID, Business name, Item ID, Item Name, order local area, quantity produced, and Product sales among others.

** Research Questions that aided this project:**

What product had the highest sales by month? What local government area produced the highest product sales? The top 5 local government areas with the highest quantity ordered? The least 5 quantities ordered by the local government area? Which knorr product had the highest sales?

**Data Wrangling**

This step involves loading the dataset, cleaning the dataset, and trimming it.

General Properties
![Screenshot_20220611-055408.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1654927573621/_td_7sjr9.png align="left")

![Screenshot_20220611-055540.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1654927781069/5exb-oIQx.png align="left")

**Cleaning the data**
- Here, I first remove all duplicates present in the dataset.
- The next step involves checking the number of null values present in each column.
- A new column of postal code and month was added and merged into the data.
![Screenshot_20220611-055507.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1654927852740/H64BL3upu.png align="left") 
![Screenshot_20220611-071450.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1654928269641/zR1rdzcA0.png align="left")


### Exploratory Data Analysis

**Data Modelling**
- The Data model was created to aid visual representation and show relationships among the categories.

![FQYlxpsn4.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1654922147850/YC-Ql8HHG.png align="left")

**Data Visualization**

**Research questions 1&2
**
What product had the highest sales by month? Which local government area had the most sales?

![month and local government.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1658140355094/UWB__Vewb.png align="left")



**Research questions 3&4**

The top and least 5 local government areas with the quantity of products ordered

![top5 and botom 5.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1658140431081/k_vizyLVj.png align="left")

**Research question 5**

Which knorr product had the highest sales?

![sales month and product.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1658140455551/BkRdP2dcB.png align="left")
 
### Conclusion 
In the first section, after the analysis of the product with the highest sales by month and the local government with the most sales, I concluded that March had the highest sales by month and the Local Government Area with the most sales is Oshodi-Isolo (49M). in the second section, the top 5 Local Government Areas with quantity order are, Oshodi-Isolo, Alimosho, Eti Osa, Ikeja, Kosofe. The bottom 5 Local Government Areas are, Ifako-Ijaye, Lagos Mainland, Agege, Mushin, Ikorodu. Finally, I was able to determine the Knorr product with the highest sales in this analysis, which is Knorr Chicken 17x50x8g. 

### Limitations
Data scrapping was my major limitation. However, I managed to fix this and got the dataset ready. Lastly, In the second section, the quantity order by local government was quite many to analyze, hence I analyzed the top and bottom 5. 


### References
Kaggle.com 

