# Kickstarting with Excel


## Overview of Project
The dataset Kickstarter shows various campaigns and their outcomes with cost of the project and time needed to accomplish it from various countries.
Louise need some information for her project and she need to do various analysis to check the outcomes of various projects
The Goal column shows the cost of each project and Pledge column shows the
amount of money made by each campaigns,using filter will help Louise to see relevant data information
which will help Louise to check the outcomes and if that has any significant impact with country and time of the year

![](Images/Picture1.png?raw=true)


### Purpose
Lousie  is planning to  do researches in various campaigns so that Louise can visualize the data better and the outcomes of each project,though she is interested
in the area of "theater" and "play"so she need to look at the cost of the project, and the amount of money that each project has made plus number of backers supported
and what is the outcomes of that particular project.
She need to do various data analysis to see if Play and Threatre will be
good to start with.She estimated  a total cost of $12000 for  her project "Play" and she
is planning to do "Theatre"as her future project particularly in Great Britain with a budget of 4000 pound .
So we need to check if that amount is good for that project and if the outcomes will be successful. 


## Analysis and Challenges
Some of the campaigns missed their goal amount by a small margin,so a new column called Percentage Funded was created which determine how much of the  campaign's goal
was met,using Goal and Pledged columns.
Average Donation is another column which has been added using Goal and Backers columns.
Pivot table for US shows overall trend of suuceeful rate of US
Pivot Tables and Pivot Chart has been used in order to see  all the information specfic to Theater catagories, for that we break up "Category and Subcategory" into "Parent Category" 
and "SubCategory" to visualize the date specific to "Theater" category.
By using filters, we can see that theater follows the overall trend there is a spike of successful campaigns that began in June
It helps to conclude that 604 Kickstarter campaigns
for plays in Great Britain, the "theater" category is the most successful.

From the "Outcomes Based on Launch Date" we can see that the month of  May and June is the  greatest successful months ,
so June seems to be better to launch the campaign. and at the same time the months of January,June,
July and October  had same number of Failed Campaigns launched.

Using Filter in the "Category Statistics" worksheet if we select only "Theater" at the parent category we can see that "successful plays is 694","successful music is 60" and 
"successful spaces is 85"

Using Statistical Components will help Louise to deepen her analysis,wheather the data is clustered at one point or spread out.Central Tendency refers to the tendency
of data to be toward the middle of the dataset.The three key measures of central tendency are the mean, median, and mode.
Measures of spread include range, variance, standard deviation, and quartiles. 
The mean of each distribution is around the 3rd quartile, so the data follows similar distributions in each subset.
The standard deviations are larger than the mean, which means everything below the mean is considered "close" to the center.
Some large values are driving all of these distributions. The standard deviations are all roughly twice the IQR in each distribution, except in the failed Kickstarters,
where the standard deviation is closer to three times the IQR. 
There must be some failed Kickstarters with really high goals!
With the help of Outliers Concept Louise could use to better plan her campaign by eliminating extreme data points that are not representative of the data . 
There are two main techniques for determining outliers, and each technique uses a measure of central tendency and a measure of spread.
They are:
    1.The mean and standard deviation together.
    2.The median and interquartile range (IQR) together.
Louise is interested in researching musicals in Great Britain for a future project with an estimated budget of £4,000.
To present Louise with the big picture, we will use box plots using statistical computations.  
Using Box and Whiskers Plot  from these plots, we can see that the mean campaign goal is around £4,000.
This is outside of the range of outliers for amount pledged, so Louise should probably try to get her play produced for less than £4,000. 
Half of the campaign goals are less than £2,000,which is just over the 3rd quartile for amounts pledged.  
 
    



### Analysis of Outcomes Based on Launch Date

From the "Outcomes Based on Launch Date" we can see that the parent category "Theater" is at highest success rate in the month of May and June,
and at the same time the months of January,June,July and October  had same number of Failed Campaigns launched.

### Analysis of Outcomes Based on Goals
From the "Outcomes Based on Goals" we can see if the goal amount is less than 1000 the succesful rate is highest 76%,
and as the goal amt increases the successful rate decreases,if the goal amount is between 15000 to 19999 the successful rate and failed rate is 50:50.
 

### Challenges and Difficulties Encountered
1. It is difficult to understand / interpret why some projects got cancelled. Was it because the project realized that the pledge would never match the goal? Or was it because of some other reason related to the project itself?
2. It is difficult to interpret live data. Some of the live data is already successful as pledge > goal. But it is difficult to include these data into the 'success' projects even though they are successful
It is challenging to classify live projects as either successful or failure even though a closer analysis can probably tell if the project is already successful or will most probably become a failure.



## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

   Theater is the most successful in the month of May and June.
   January,June,July and October has same number of Failed Campaigns.

- What can you conclude about the Outcomes based on Goals?
  If the goal amount is less then the chances of successful rate is higher. 

- What are some limitations of this dataset?

1. Name of creator / owner of the projects, their credentials, experience, popularity etc. This data can be a driver in determining the success / failure of a project
2. More data points about the project might be helpful. Information like when will the project start, how long will the project take to complete etc. can be insightful.
3. More information about the backers, like their age, income range etc. might help target backers more effectively for a particular project

- What are some other possible tables and/or graphs that we could create?
1. Success / failure line plot with the "length of the fundraiser"
2. Success / failure line plot with the country
3. Success / failure line plot with the Year
4. Success / failure line plot with the Backer count, and the average contribution / backer.


