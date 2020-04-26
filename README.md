# Analysis of Kickstarter Campaigns

Kickstarter is a crowdfunding platform with the mission to "help bring creative projects to life", where a prospective individual can find financial supporters, "backers", for campaigns. Fortunately, the data provided can give insight that may help maximise chances of success.

Data from 4114 Kickstarter campaigns from 2009 to 2017 was analysed and outcomes across campaigns were considered, as shown in the chart below.

![Parent Category Outcomes](https://github.com/Alyssa-CG/Module1-Kickstarter-project/blob/master/Parent%20Category%20Outcomes%20Chart.png)

At first glace, it is evident that theater was the most common type of Kickstarter campaign during this eight year period, across the 21 countries from which data was collected. Theater had the largest number of successful campaigns, but also the largest number of failed campaigns, which begs further analysis.

![Subcategory Outcomes](https://github.com/Alyssa-CG/Module1-Kickstarter-project/blob/master/Subcategory%20Outcomes.png)

The second and chart shows that Plays, a subcategory of Theater, were the most common type of campaign. As shown in the following charts, plays were also successful more often than not, and had a relatively higher success rate than the other theater campaigns, spaces or musicals.

![Theater Category Outcomes](https://github.com/Alyssa-CG/Module1-Kickstarter-Analysis/blob/master/Theater%20Category%20Outcomes.png)

![Parent and Subcategory Outcomes](https://github.com/Alyssa-CG/Module1-Kickstarter-project/blob/master/Subcategory%20Outcomes-%20plays.png)

This alone does not give enough information, so month of launch, goal and pledge amounts were evaluated for the Kickstarter campaigns.

![Outcome Based on Month Launched](https://github.com/Alyssa-CG/Module1-Kickstarter-project/blob/master/Outcomes%20Based%20on%20Month%20Launched.png)

![Goal and Pledged Quartiles for Great Britain](https://github.com/Alyssa-CG/Module1-Kickstarter-project/blob/master/Goal%20and%20Pledge%20Quartiles%20for%20Great%20Britain%20Kickstarter%20Musicals.png)

After evaluating the data, I would recommend that if a play is selected for a Kickstarter campaign, it be launched in May which appears to be correlated with the highest successes. Target goal amount should also be realistic, so it may be worth considering what past values were successful in different regions. Other factors must be considered when planning the kickstarter campaign, such as the state of the economy (recession or even pandemic versus boom), how the campaign will be promoted (sponsors, spokespersons etc) and where the initial resources (advertising money, manpower) will come from.



### Challenge

Overall, the rate of success was inversely correlated with goal amount, with some variability between the cases, as depicted in the following chart. 

![Outcomes Based on Goal Amount-Plays](https://github.com/Alyssa-CG/Module1-Kickstarter-Analysis/blob/master/Outcomes%20Based%20on%20Goal%20Amounts-%20Plays.png)

The plays with the lowest goal amounts of less than $1,000 had the highest percentage rate of success at 76%, while the highest goal amounts over $50,000 only had a 13% success rate. The general trend is not without exception however, as there was a peak in success rates around the $35,000 to $45,000 range, where factors others than a conservative goal may have been more significant in determining success. Perhaps campaigners with goals in that range had better strategies for attracting backers such better marketing or a respected public figure openly promoting their campaign. 


Month of launch of a campaign was also correlated with success rates for theater campaigns, as shown below.

![Outcomes Based on Launch Date](https://github.com/Alyssa-CG/Module1-Kickstarter-Analysis/blob/master/Outcomes%20Based%20on%20Launch%20Date-Theater.png)

Theater campaigns were generally less successful when launched at the beginning or end of the year, but peaked in success around the middle of the year, with December as the least commonly successful month for launching campaigns and May as the most commonly successful. This may be tied a number of factors, perhaps competing interests with holidays, festivities and gift-giving at the end of the year or increasing interest in the arts and leisure time in the Spring and Summer months.


There was also interest in how the duration of the campaign may affect success and it does seem that success peaks in cases when the duration is approximately one month long, with several smaller peaks for campaigns with shorter durations and another small peak around the two month point. 

![Outcomes Based on Duration- Plays](https://github.com/Alyssa-CG/Module1-Kickstarter-Analysis/blob/master/Outcomes%20Based%20on%20Duration%20of%20Campaign-%20Plays.png)

![Outcomes Based on Duration- Theater](https://github.com/Alyssa-CG/Module1-Kickstarter-Analysis/blob/master/Outcomes%20Based%20on%20Duration%20of%20Campaign-%20Theater.png)

This shows that most successful campaigns have a duration of one month or less and relatively few are successful after this point, perhaps a point that is reiterated by the observation that the average length of a Kickstarter campaign in our dataset is 33 days. It is also worth noting that because the average campaign is 33 days, around this point there is also a sharp increase in cancelled and failed campaigns.


As mentioned before, there are a number of factors that need to be considered when planning a campaign. The state of the economy, initial resources, advertising, location, time of year and more need to be considered and optimised for the particular type of campaign chosen. Shortcomings of the dataset include that it may not be accurate or comprehensive and it includes campaigns as far back as 2009, which may or may not be representative or comparable to campaigns today for several reasons. 2009 was closer connected to a recession in the United States and advertising tools and technology has improved quite a lot since then. The dataset also lacks some clarification for what it means if a Kickstarter was a Staff pick, spotlighted or how factors such as duration are determined which could all be useful to inform decision-making. There are also factors not captured by the dataset such as how much experience the campaign team has, how large or small the campaign team is and whether or not they have a strong strategy for campaigning.

For additional information, it would be interesting to compare similar categories across specific countries of launch to observe if specific campaigns do better in specific countries. For example, although their samples are small, it's interesting to observe the countries where the majority of Theater campaigns are not successful such as Denmark, where only half their Theater campaigns have succeeded, or Australia where less than half have succeeded. 

It may be worthwhile to plot more charts based on duration as the ones demonstrated above, but also showing percentage of success at these points rather than count. At times the comparisons in this analysis seemed inconsistent, comparing Theater outcomes to Play outcomes and counts to percentages. To ensure trends were consistent across the categories, I believe it extremely beneficial to plot and consider more charts by categories being evaluated, even if ultimately all do not need to be featured in a concise final report. Other charts that can be viewed can include those showing rate of success relative to launch date (not only count), success counts and/or rates by year of launch, country of launch, number of backers, average pledge amounts and whether the campaign was a staff pick or spotlighted.

Ultimately, the best recommendation we can give from this current data and analysis is that the launching a Theater or Play campaign in May for a duration of 33 days with a goal of under $1,000 or $5,000 would be correlated with a very high chance of success. 
