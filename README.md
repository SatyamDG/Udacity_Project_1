# Udacity_Project_1
This Repo contains all files &amp; medium blog related to EDA
## Data Overview

The dataset consists information collected from car sale advertisements for study/practice purpose where most of them are used cars.
The dataset comprises of 9576 observations of 10 columns. Below is a table showing names of all the columns and their description.

  ColumnName	|    Description
  
  car	       -->    Manufacturer brand
  
  price	        -->   Sellers price in advertisement (in USD)
  
  body	        -->  Car body type
  
  mileage	    -->    as mentioned in advertisement (‘000 Km)
  
  engV	        -->    rounded engine volume (‘000 cubic cm)
  
  engType	    -->    type of fuel (“Other” in this case should be treated as NA)
  
  registration  -->	 whether car registered in Ukraine or not
  
  year	        -->    year of production
  
  model	        -->    specific model name
  
  drive	        -->    drive type




## Problem Statement

Data used in this analysis is taken from [link](https://raw.githubusercontent.com/insaid2018/Term-1/master/Data/Projects/car_sales.csv "link"), there are various brands,type,etc of cars included in the dataset which is explored in this case study.

Our main objective for data analysis is to get the solution for below mentioned Business question:

1. Which brand of cars is most selling brand depending on user profiles?
2. which type of cars are more selling?
3. What are the factors affecting the price of cars?

## Packages Required

`import numpy as np`                                                
`import pandas as pd`                                             
`import pandas_profiling`
`import matplotlib.pyplot as plt`                               
`import seaborn as sns`                                           
`%matplotlib inline`
`sns.set()`

## Conclusion

**1. Which brand of cars is most selling brand ?**


* From above analysis we can conclude that ,Volkswagen and Mercedes-Benz are top most brands on sale and hence these would be    preferred choices for high profile people.


**2. which body type of cars are more selling?**

* "sedan" type of body having maximum registration/sale over the years. This shows People prefers sedan type of body mostly and hence this information can be use for achieving max sale and to figure out production of units.


**3. What are the factors affecting the price of cars?**

*  Price changing accordingly based on mileage value, So price is varying based on mileage too and this should be consider as a factor for the calculation

* Petrol engine type is preferred over diesel & gas.


**For detailed analysis please check [Notebook](https://github.com/SatyamDG/Udacity_Project_1/blob/master/Udacity_Project_1.ipynb "Notebook")**

**For easy understanding the conclusion in Visual format please refer medium  blog**

Feel free to use this repo
