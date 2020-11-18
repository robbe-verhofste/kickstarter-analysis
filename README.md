# Kickstarting with Excel

## Overview of Project
In this project I analyzed kickstarter data to for a client interested in launching the kickstarter campaign. I analyzed for several components, including launch date and optimal funding goals.
### Purpose
The primary purpose in this analysis was to determine the optimal launch date and funding goal for the client's kickstarter campaign.
## Analysis and Challenges
For the outcomes based on goals analysis, I wanted the goal range in the analysis to be parametric, rather than manual as the instructions indicated. This would allow the client to individually goal bins if she were interested in doing so, and it prevented me from needing to manually modify the "successful", "failed", and "canceled" code. This was more difficult than I had anticipated for two reasons:
#### A)
  I was not aware that I needed to input the "&" symbol before the cell reference, and
#### B)
  I generated several incorrect charts, and I was unaware if my formula was incorrect or if the error originated elsewhere. The error ended up resulting from incorrect usage of the filter (for "plays" in the formula. I am also not sure why my "live" trend looks different from the example in Canvas.
#### code:
  =COUNTIFS(Kickstarter!$D:$D,">=" & $B2, Kickstarter!$D:$D, "<=" & $C2,Kickstarter!$F:$F,D$1, Kickstarter!P:P,"plays")
### Analysis of Outcomes Based on Launch Date
Kickstarters under the Theater category, from 2009-2017 in Great Brittan, were most successful if they launched in May.
### Analysis of Outcomes Based on Goals
Kickstarter goals under $5000 had an average success rate of 74%, significantly higher than the average success of all campaigns (66% success rate) and higher than any other goal range. If the client requires a greater budget, goals between $35,000 and $45,000 see the next highest rate of success, at 67%.
### Challenges and Difficulties Encountered
One challenge in this analysis is interpreting the statistical significance between success rates based on goals. Knowing statistical significance here would increase the rigor of the recommendations.
## Results

# What are two conclusions you can draw about the Outcomes based on Launch Date?

Kickstarters under the Theater category, from 2009-2017 in Great Brittan, were most successful if they launched in May. Projects launched in December, however, are most likely to fail.

# What can you conclude about the Outcomes based on Goals?

Projects with goals greater than $45,000 are most likely to fail, followed by projects with goals between $25,000-$35,000. Projects with goals less than $5,000 have the greatest success rate.

# What are some limitations of this dataset?

There are only 1,112 projects in the theater category, by incorporating a larger dataset, different trends may become clear. We also have no analyzed marco-economic trends - (e.g. did a recession in a given year cause theater support to decrease?

# What are some other possible tables and/or graphs that we could create?

Comparison of success based on year to draw inferences based on larger economic trends (e.g. do success rates change in election years?). Do types of theater campaigns result in different outcomes? Do the descriptions play an important role?
