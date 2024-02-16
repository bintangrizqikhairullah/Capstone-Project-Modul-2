# Green Borough Taxi Analysis

Hi everyone, in this project i will try to discover hidden pattern and insights from the NYC borough taxi trip data by performing data analysis, these findings can be used by taxi cab companies or even individual drivers to improve their profit or minimize operating cost.

# Source Data 
<p align="center">
<img src="images/NYC.png" alt="Image Description" width="300"/>
</p>

The main data that being used in this analysis was gained from the New York City Taxi and Limousine Commission (NYC TLC), each rows represent a green taxi trip. the secondary data that being used was gained from the nyc open data which contains information of trip location and shape data.

# Business Understanding
<p align="center">
<img src="images/Boro-Taxi-4.png" alt="Image Description" width="300"/>
</p>
Boro taxis or green taxi are taxicabs in New York City that are allowed to pick up passengers (street hails or calls) in outer boroughs (excluding John F. Kennedy International Airport and LaGuardia Airport unless arranged in advance) and in Manhattan above East 96th and West 110th Streets.

# Problems to be solved

After diving into the bussiness process, here are some problems that i can help to solve by using the data:
<ol>
  <li>When is the best time to allocate the taxi fleet or drive a taxi?</li>
  <li>Is the borough taxi distribution to other borough is even? </li>
  <li>How to improve the borough taxi business in other borough ?</li>
</ol>

# Data Cleaning

Data cleaning plays a pivotal role in data analysis as the quality and validity of insights are very dependant on data cleaning
<ol>
  <li> Handling Missing Values ?</li>
  <li> Outlier Identification </li>
  <li>How to improve the borough taxi business in other borough ?</li>
</ol>

## Missing Values

![image](https://github.com/bintangrizqikhairullah/Green-Borough-Taxi-Trip-Analysis/assets/101108509/c9ddcc22-5290-411e-8f47-306b9ffe9af1)

The data have 7 columns with missing value, The column "ehail_fee" has all it's value missing, while other columun has an average of 6.35% missing value.The column "ehail_fee" is dropped because all of it's value are missing The rows with missing values are dropped because imputation would probably lead to bias and there are no patterns in these missing value beside it happens in the same observation.

# Data Analysis

# Peak Day Analysis

![image](https://github.com/bintangrizqikhairullah/Green-Borough-Taxi-Trip-Analysis/assets/101108509/62be0ead-9c70-458e-98b6-27de1a097a91)

![image](https://github.com/bintangrizqikhairullah/Green-Borough-Taxi-Trip-Analysis/assets/101108509/fedf36b5-bc71-4d98-9324-a35597fe3d61)

# Peak Hour Analysis

![image](https://github.com/bintangrizqikhairullah/Green-Borough-Taxi-Trip-Analysis/assets/101108509/bcdece7e-1e64-43ac-8d98-4eb65447a66b)
