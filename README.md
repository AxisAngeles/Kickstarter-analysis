# Kickstarting with Excel

## Overview of Project

### Purpose
This next analysis is mainly focused in building a kickstarter benchmark to compare our client results based on our two main variables: launch date and funding goal. 
#

## Overall Analysis and Challenges
Between the 48 different play campaigns worldide launched in June and July 2016, **"FEVER" was among the 27% of the campaigns that failed**.

Once the data wrangling and cleansing were overcomed, the main challenge was to identify which of the different elements could be responsible for our client's outcome.

This is why, the following paragraphs will adress two main hypothesis: 
* Was it related to timming?
* Was the resulted driven by a poorly defined goal?


### Analysis of Outcomes Based on Launch Date
The first step of the analysis consisted in finding patterns or correlation between the launch date and the probaility of success.

This resulted in the followting chart:

![Launch Date](\Resources\Theater_Outcomes_vs_Launch.png)

Based on this, it's possible to see that campaigns launched between May and July tend to be more successfull which was not the case for our client's _FEVER_ play.


### Analysis of Outcomes Based on Goals
On the other hand, the Outcomes analysis revealed that the second hypothesis was not so accurate either.

When analyzed, the Goal factor didn't seem to be relevant to find the reason for the failed result as shown on the next graph:

![Goal Outcomes](\Resources\Outcomes_vs_Goals.png)


### Challenges and Difficulties Encountered
Regarding the overall challenge, we've encountered some technical difficulties during the making of this summary, mainly at this md coding, which was adress with further investigation and, lets face it, trial and error.

There's also a remmaining challenge in finding a concrete answer to FEVER's results. This is why the next steps should also consider working on differente variables like the funding timming or average donation.

#
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  1. It does seems to be a seasonality involed when launching successfull campaigns.
  2. Failed campaigns have an even or flat distribution along the year, so there mush be other elements correlated to that outcome.

- What can you conclude about the Outcomes based on Goals?
  1. First, the initial line chart it's not sufficient to draw any significant conclussion.
  2. As expected, the higest goals are most likely to underperfom or fail.

- What are some limitations of this dataset?
  * It can allways be more helpful to have broader datasets, (i.e bigger campaign samples).
  * We have no information about the types of campaigns or about the backers.

- What are some other possible tables and/or graphs that we could create?
  * Using the same pivot table, we could do further research to compare campaigns lauched at simmilar conditions (dates or countries).
  * A box and whisker chart could also help to identify possible outliers for fair comparissons.
  * A dispersion diagram between goals and backers could help us identify the different reach of each campaign: was it funded by few backers with high contributions? or was it funded by many people?
