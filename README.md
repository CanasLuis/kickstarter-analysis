# kickstarter-analysis

## Overview of Project
### Purpose

With a database given, the pourpose is to undesrtand how are the fundraising behaving in terms of having success, fail, or being cancelled. We can study the goals amount and the types of each one of them and determine factors of success.


## Analysis and Challenges
###Overview
As mentioned, the given information contains detail of each fundraising like name, dates, goal, pledge, country, etc. As follows:

![detailed info](https://user-images.githubusercontent.com/108499271/177900381-b03cfce8-fba0-475f-adb1-3dd2a022c47d.png)

With that information, the first and quick analysis might be done using simple Excel tools, for example, we know that we have 4,114 campaings and proyects from different countries too. In addition, we can also get to known a little better our data base:

    -MAX	Goal Amount $100,000,000 
    -MIN	Goal Amount $1 
    -AVERAGE	 Goal Amount $71,939 
    -MEDIAN	 Goal Amount $5,000 

###Challenges
-Main challenge is related to the dates, since the format we have is unfamiliar with the usually format we see and work with, for that reason, it is needed to be updated using a formula. this will allow us to allocate information using periods of time

-Another potential challenge is related to the Pivot Tables if you are not quite familiar with them. Getting a good use of them is when we can obtain the best potential of the information we have.


The month with most successful fundraisings is May, showing a big increase from Apr, with 40 succesful cases. In addition, failed and canceled fundraisings didn´t grow that much, from April to May. 
Biggest number of failed cases happened in Oct, despite of that, this is the only month with no canceled campaings.

The campaing with the highest percentage funded had a goal of 1.00 USD, and pledged more thatn 22 thousand USD

##Results
### Analysis of Outcomes Based on Launch Date

-December was the worst month for campaings, with almost the same successful cases than failed ones. In total, failed plus canceled are more than the successful ones
36% of the fundairisng campaings failed during the year, having just a rate of success of 61%
-In October any of the campaings were canceled

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/108499271/177901460-992c1e77-53ed-480f-8beb-98db28d71618.png)

### Analysis of Outcomes Based on Goals

-None of the campaings with subcategory play was canceled. 
-In addition, the campaings with a goal of less than 1000 have a higher successful rate.
-The highest percentage funded was for a campaing with a goal of $1 USD, raising $22,603 USD.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/108499271/177901545-a615ff8d-877a-4bdd-95e7-42fe7ea9279c.png)

### Limitations of the dataset
A lot can be done with this dataset, however there are few things that might be improved and help with the data analysis, like:
-As mentioned, date has to be adjusted to become readable
-I would be important to have detail on the canceled fundraising so user can understand what is the main reason of that
-Sub cattegory had to be extracted for more consistent type of information, this can also be improved. 

