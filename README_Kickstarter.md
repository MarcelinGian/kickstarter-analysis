# Kickstarter-Analysis

## Overview of Project

### Purpose
##### Louise is a playwrite whose Kickstarter crowdfunding campaign for her play, "Fever," has come close to its funding goal of $12,000 USD in a short amount of time. This analysis of excel data will help Louise better understand how different campaigns fared in relation to their launch dates and their funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
##### For this section of my analysis I used data in the Kickstarter worksheet to create a pivot table. I then filtered the pivot table based on "Parent Category" (which was set to "theater) & "Years" to see how a theater campaign's Launch Date correlated with the campaign's subsequent success or failure. Finally, I created a line graph using this filtered data.
 
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/105818879/171560330-dbc35a5d-ad53-4559-a528-51d769b5716d.png)

### Analysis of Outcomes Based on Goals
##### For this section of my analysis I used the Kickstarter data to create a visualization of the percentage of successful, failed, and canceled plays based on the funding goal amount. First I used the excel "COUNTIFS()" function to section the data in increments by fundraising goal. With these numbers calculated I then used the "SUM()" function to add up the successful, failed, and canceled campaign totals by aforementioned increments. Lastly- I used the "ROUND()" function to translate these numbers into percentages that I could use in my pivot chart.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/105818879/171565312-c9994b61-141c-472a-a309-cabd13b7b4c0.png)

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  - Based on the excel data we can see that campaigns in the "theater" category were most successful when they were launched in the month of May- follwed by the months of June and then July.

- What can you conclude about the Outcomes based on Goals?
  - Based on my excel data calculations we can see that play-category crowdfunding campaigns with fundraising goals of less than $5,000 had the highest probability of success compared to capaigns with higher goals.

- What are some limitations of this dataset?
  - This dataset does not explicilty display play-specific outcomes based on launch date, rather it graphs all of the "theater" category- which includes physical theater spaces, musicals, as well as plays. This limitation makes the data less relevant to Louise because she's trying to fund a play specifically.
  
- What are some other possible tables and/or graphs that we could create?
  - We could create an "Outcomes Based on Launch Date" graph specifically for the play subcategory. 
