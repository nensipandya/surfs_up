# surfs_up

## Overview
------------------------------------------------------------------------------------------------------------------------------------------------------------------------

The purpose of the surfs_up analysis is to review the dataset of weather conditions that has been stored in a SQLite database. SQLite database provides the information, which will help to convince W. Avy, an investor, who will help you to open Surf n'Shake shop in Oahu, Hawaii. The idea is that the shope will sell surfs board and icecream throughout  the year. But W. Avy is hesitant to decide on that because in the past he had the similar businessthat failed due to the weather conditions. In order to get the confidence of the investor and get this investor on board, we need to provide statical analyis of weather condition in Oahu. This analysis will convince the investor that this will be the successful business.

In order to explore the SQLite database ( which is version of SQL that lives in the computer / mobile , and run faster), we need to use SQLAlchemy, which is qurey tool designed for SQLite and integration of statistical analysis with data from analysis. Throughout the analyis , we will use Jupyter Notebook to import dependencies and create code to pull the data from SQLite database. Some of the feature / functions that we need to use for this module include:
 
  1) SQLAlchemy ORM - Object Relational Mapper
  2) SQLAlchemy Create Engine - primary purpose is to set up the ability to query a SQLite database
  3) SQLAlchemy Automap Base - creates a base class for an automap schema in SQLAlchemy
  4) SQLAlchemy Reflect Tables - reflect our tables with the prepare() function
  5) Session - Create Session Link to the Database
  6) SQLAlchemy extract
  
 
Finally, we used FLask application, which allows to create Python applications and then share the results of those applications with others via a webpage, making it a powerful tool for data analysis and visualization.

## Results
----------------------------------------------------------------------------------------------------------------------------------------------------------------------

When we pull the data, we first looked the precipitation for the one year timeframe from August 23, 2016 to August 23, 2017. 

![image](https://user-images.githubusercontent.com/107137215/184516675-df067fb8-ce25-49fb-adb3-bce6e72450d9.png)

![image](https://user-images.githubusercontent.com/107137215/184516691-ea98b004-3012-4e5b-bc33-a249e56d3e18.png)
 
By looking at this analysis, it shows that there was mostly sunny throughout that year timeframe.

![image](https://user-images.githubusercontent.com/107137215/184516741-527fca7e-6842-4a8e-a740-5512fcb5e356.png)

![image](https://user-images.githubusercontent.com/107137215/184516865-5684109c-a448-454e-8b9e-ef45cce3b5cc.png)


We also collect the data for different stations that will actively collecting precipitation data. There were total 9 stations and the most active station is 'USC00519281'. The results show that the avergae temperature os 73 degree F and the maximum temperature is 83 degree F  and minimum temperature is 59 degree F.

W. Avy likes the above analysis, but he wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu.

![image](https://user-images.githubusercontent.com/107137215/184516924-8ad5b7cf-b37f-469f-8ed8-9da50a002f7f.png)  ![image](https://user-images.githubusercontent.com/107137215/184516930-d70e8403-64c7-4eea-8c07-7429af391e65.png)

We recorded the temperature data for the month of June and December and the results shows:
-> The average temperature for June is 74 degree F and for December is 71 degree F
-> By looking at the results, the average temperature between June and December month is almost similar.
-> The assumption is that the temperature does not have dramatic fluctuations throughout the year.


## Summary
---------------------------------------------------------------------------------------------------------------------------------------------------------------------

In summary, the temperature, in Oahu, is relatively same throughout the year. The avergae temperature is in the 70's.

![image](https://user-images.githubusercontent.com/107137215/184517259-0c9e916e-60a6-4844-8f5e-81141ff4856c.png) ![image](https://user-images.githubusercontent.com/107137215/184517263-b88ffa2f-ee9b-4028-bdc7-fd05db4679a5.png)

Looking at the precipitation and the temperature proves that investing in Surf n' Shake is a good business venture and that Oahu, Hawaii is the ideal location.

But to get more information, we did further analysis of month os March, July, September and October. Here's are the results of temperature and precipitation data for these months.

![image](https://user-images.githubusercontent.com/107137215/184541206-0057eb18-f658-4c1a-9077-73df0b995612.png) ![image](https://user-images.githubusercontent.com/107137215/184541220-79cdd8a1-4017-4599-98d0-5d799beeb303.png) ![image](https://user-images.githubusercontent.com/107137215/184541240-68515bfa-0ee6-423d-995b-62e80cb332c4.png) ![image](https://user-images.githubusercontent.com/107137215/184541257-3026f7c4-d86b-4bd8-a13a-dff85b4c5584.png)


By looking at these data, it's confirm that the average temperature is in 70's. There is no doubt that Surf n' Shake is going to a successful business in Oahu, Hawaii.
