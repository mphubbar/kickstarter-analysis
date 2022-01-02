# Kickstarting with Excel

## Overview of Project
The project was to help Louise analyze successful and failed campaigns for plays so that she could determine the optimal launch date and funding goal.

### Purpose
The purpose of the project was to determine the best launch date and fund-raising goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
To analyze the impact of different launch dates, I created a pivot table filtering based on Parent Category and Years, I added date created to the rows and outcomes to the columns. I then filtered based on columns so successful campaigns showed up first. I struggled getting the rows to show months as initially they showed quarters, so I had to adjust the parameters of the row (Axis Categories) to get it to be months instead of quarters.

![Launches_Pivot_Formulas](https://user-images.githubusercontent.com/93684808/147885764-2c6f65c4-a95b-43e3-bfdb-3d93561a60d5.png)

### Analysis of Outcomes Based on Goals
To analyze the impact of different fundraising goals I had to build a new table and populate it using coutifs. I struggled to get the correct criteria in the correct order for the different campaigns and ranges of goals. I spent some time googling and watching YouTube videos and experimenting with different formulas before I was able to get the correct formulas as shown below.

![Outcome_Goals_Formulas](https://user-images.githubusercontent.com/93684808/147885785-94016588-32c5-4c7f-b0aa-901ad2efe29f.png)


### Challenges and Difficulties Encountered
As described above, the main difficulties I encountered were in adjusting the categories, criteria, and formatting of the pivot table and in structuring the countifs formulas correctly. Google, YouTube, and trial and error proved effective solutions.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
     - Based on the chart below we can conclude that the best time to launch a campaign is in May or June. June might be better than May for launching a campaign, given the number of failed campaigns also peaks in May.
     - Both failed campaigns increase and successful campaigns decrease significantly if launched later in the year (Oct - Dec). And December is the only month where there is not a significant positive spread between the number of successful and number of failed campaigns, which likely means December is the worst month to launch.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/93684808/147885815-c84d2ea0-f814-4034-9ccf-97f366ef85d0.png)


- What can you conclude about the Outcomes based on Goals?
     - Campaigns with lower goals were more successful, with the highest percentage of successful campaigns occurring below $5,000.
     - Campaigns with goals less than $20,000 had more successful results than failures, while campaigns above $20,000 had more failures than successes.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/93684808/147885843-2d400673-8e4a-4be2-814a-df24b5325c83.png)

- What are some limitations of this dataset?
     - This dataset does not provide any clues or data as to why spring launches and lower campaign goals seem to work better.
     - The dataset also does not provide data on types of plays (drama vs. comedy) and how therefore we cannot figure out what types of plays are more successful.
     - There is no data on attendance of the plays so we cannot see if fundraising is correlated with attendance.
     - Success is defined relative to the goal, but we do not know how the fundraising goal compared to the actual cost of the play so some failed campaigns relative to the goal may still have generated enough money to cover the costs of the play.

- What are some other possible tables and/or graphs that we could create?
     - We could compare % of goal or successful campaigns relative to staff picks to see if there were any correlation between staff picks and successful campaigns.
     - We could do more analysis around successful campaigns and what the average pledge was and average number of backers so that donation asks could be more specific.
     - We could also deconstruct the number of words in the title and compare that to the percentage funded to see if shorter or longer titles had better / more successful campaigns.
     - We could build a table that showed average donation relative to outcomes.
