# Kickstarting with Excel

## Overview of Project
Analyzing Kickstarter dataset to determine outcomes based on launch date and goal.

### Purpose
The purpose of this project is to find how different campaigns performed wrt to their launch date and goals.

## Analysis and Challenges
Pivot table and line chart are two feautres used in analyzing the dataset which gives us clear picture of results. Determining key columns and using correct filters gives us accurate analysis results.

### Analysis of Outcomes Based on Launch Date
This analysis was performed only on "theatre" catergory as per client requirement. A pivot table and line chart is created from main dataset using outcomes and launch date. 

![image](https://user-images.githubusercontent.com/83181834/116597779-df711880-a8da-11eb-9595-6f26ff107400.png)

### Analysis of Outcomes Based on Goals
This analysis required many derived column calcuations to determine the outcomes based on goal. Once we created a smaller dataset of derived columns based on outcomes, goal and subcategory, a line chart is best fit to show the results.

![image](https://user-images.githubusercontent.com/83181834/116597823-ec8e0780-a8da-11eb-9d23-6c339ebe242d.png)


### Challenges and Difficulties Encountered
Some challenged encountered in this analysis:
  1. Determining Group by values used in pivot table of Outcomes by launch date. Incorrect group by values leads to wrong graph
  2. Outcomes based on goal table is entirely made of derived columns hence the chance of error is more in this dataset.
  3. COUNTIFS function is used in Outcomes based on goal derived column. While the business rules are clear chances of missing or erroring of catergories are high.

## Results

- Outcomes based on Launch Date - Analysis conclusion
  1. Chances of campaing being successful are high if the campaigns are launched between May-June.
  2. Q1 and Q4 is not an ideal time to launch any new campaigns.


- Outcomes based on Goals - Analysis conclusion
  1. Most of the plays campaigns are successfull if the goal amount is less than $10000.
  2. Most of the campaings are failed if the goal amount is more than $50000.

- Limitations of dataset
  1. This dataset contains "theatre" data from all over the world however some plays are popular in some countries while some are not, hence this dataset cannot mimic general theatre audience.

- New tables/graph options
  1. Outcomes based on goal results are depicted well in stacked bar chart. 
  2. Theatre outcomes by launch date table can include country filter to determine success/fail based on region.
  3. New table / chart created to analyze canceled outcomes in theatre category.
  
