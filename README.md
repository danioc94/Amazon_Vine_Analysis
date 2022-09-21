# Amazon_Vine_Analysis

## Overview of the Analysis
Using PySpark on Google Colab notebooks, we analyze a video game data set part of Amazon Vine program to determine if there is any bias toward favorable reviews between paid and unpaid subscribers. This repository also includes code to link AWS RDS DB with pgAdmin.

## Results

- We obtained the following results of paid and unpaid vine reviews:
<img width="376" alt="image" src="https://user-images.githubusercontent.com/20058842/191401951-5932cc89-813a-4e51-91f1-8bf19ce8c744.png">

- We obtained the following results of 5-Star unpaid and paid reviews:
![image](https://user-images.githubusercontent.com/20058842/191402002-cc7e44c9-42b6-4d6b-a9b2-f9b5844d2acc.png)

- The percentage of 5-Star reviews for paid and unpaid subscribers:
![image](https://user-images.githubusercontent.com/20058842/191402059-f3562eb3-24bc-4c9a-8330-c59ce7c9fb76.png)


## Summary

After viewing the final results we can see that the amount of unpaid user is very higher than the paid users. After viewing the percenatge of 5-Star reviews paid and unpaid users we can see that there are 0.48 5-Star paid reviews and 0.39 unpaid 5-Star unpaid reviews. I think these percenatges are not real indicators that there could be a bias of rating videogames with 5 stars between paid and unpaid users. There are not extreme differences between these results. There should be a new way to determine if there is any real bias or not.
