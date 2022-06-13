# Play Campaign Outcomes Based on Launch Dates and Funding Goals

## Overview

The purpose of this analysis is to compare how different play campaigns performed with regard to their launch dates and funding goals. This will give insight into when the plays should be launched in order to increase their chances of success, as well as how much their budget should be for the production.

### Analysis

To perform this analysis, I filtered through various Kickstarter campaigns to find information only on plays. From there, I was able to create comparative information using the outcomes of successful, failed, and canceled plays in relation to when the campaigns were launched. 

[Theater_Outcomes_Vs_Launch_Table](/resources/Theater_Outcomes_vs_Launch_Table.png)

To gather more information from the data, I also compared the percentage of outcomes to their funding goals to determine how much the budget affected the outcome of the play. 

[Outcomes_vs_Goals_Table](/resources/Outcomes_vs_Goals_Table.png)

### Challenges

The biggest challenge I faced, I was able to overcome by double-checking and cross referencing my data. One incorrect character within an Excel formula can greatly skew the results and with a dataset as large as the Kickstarter campaigns, it was imperative to make sure all of my data was entered correctly. I was able to utilize this to correct a mistake of using a less-than sign where a greater-than sign was needed.

### Conclusions

#### Theater Outcomes by Launch Date

[Theater_Outcomes_Vs_Launch_Table](/resources/Theater_Outcomes_vs_Launch_Table.png)

The data shows that entertainment from theaters is more successful when launched in the late Spring, early Summer months of May, June, and July, although May will offer the best chance. Additionally, December is shown to yield the lowest probability of launching a successful theater campaign.

#### Outcomes Based on Funding Goals

[Outcomes_vs_Goals](/resources/Outcomes_vs_Goals.png)

The most successful plays had a budget goal set at or below $4999.

## Limitations

This dataset does not account for specific regions within each country; something that does well on the upper East coast of the US may not fare the same in the southern states. Additionally, this Kickstarter data does not filter out economic events such as stock market crashes, pandemics, wars, and more. While it does give blurbs about each play, it does not list the data by genre, which could also play a role in the success or failure of the campaign.

## Recommendations

As of now, all of the goals and pledges are being compared as having the same weight of currency, even though they vary. Another possible table and graph we could create would be one which converts the different currencies to the same weight. For example: we would find the exchange rate between the euro and US dollar, so when we compare their financial goals, they can be more accurate. Currently, 1 euro is equal to 1.04 of the US dollar, which doesn’t sound like much but for a goal of $15000, it could mean a difference of $600 overall.
