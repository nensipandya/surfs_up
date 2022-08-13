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
  
 
