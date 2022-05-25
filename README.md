# data_1_check

## Checkpoint #1 ## 
Exploring Pandas

## Data Source ##

My data source was a free API on NBA players: https://www.balldontlie.io/api/v1/players

## Requirements ##

All need packages can be installed by the requirements.txt file. The following packages are included:
- pandas
- request

## Features Included ##

The features included for the Checkpoint 1 are: 

#### 1) Pull Data from an API ####
- I created pull the data from the above API using requests. Next, I converted it into a JSON file. Lastly, I used pandas to create a dataframe from the JSON dictionary. 

####  2) Select and Print the First 4 Rows#### 
- I applied `.head(4)` on my data frame to show the first 4 rows. 

####  3) Select and Print the 2nd and 3rd Rows #### 
- I applied `.iloc[2:4]` to determine the 2nd and 3rd rows of my dataframe. 

####  4) Find and Print Two Descriptive Statsitics #### 
- I created two new variables: avg_weight and med_weight. I determine the mean and median of the the column on the players weight. 

####  5) Write a Query ####
- I used a query to find the row with the player's first name of Jabari. I also used a query to determine the players that had a weight greater than the average weight. 
