# CitiBike Tableau Analysis

This analysis and all visualizations utilize full, unaggregated datasets from the February-June periods of 2019 and 2020. The goal of this analysis is to compare CitiBike ridership metrics from a "normal" year of rider participation and numbers from the 2020 Covid-19 lockdowns in New York City. The dataset is representative of 13+ million rides distributed between the two years of comparison.

### SARS-Cov-2 Impact and Recovery

##### Total Ridership Comparison

- The period of late March-May of 2020 saw the imposition of enforced lockdowns to slow the spread of SARS-CoV-2 (COVID-19). In aggregate, this has shown a decreased ridership of 23% in the February-July sample window compared to ridership in the same 2019 time frame. As to be expected, the greatest declines occurred early in the lockdown, with a sharp maximum decline of 87% on 3/26/2020. This trend carried through until early June, when ridership recovered to near-normal levels around 6/10/2020.

##### Bike Wear Comparison
- One positive result of the lockdown is the sharp reduction in bike wear. The most used bikes during the sample window in 2020 accumulated significantly less wear than in 2019. Most bikes in the 2020 top 30 most used received 50% less wear than their 2019 counterparts. Max wear on a single bike in 2019 was 1,552 rides, whereas max wear on a single bike in 2020 was 1,172 rides. 18 of the top 20 most ridden bikes in 2019 were within 250 rides of one another, whereas only one other bike was within that same margin more the 20 most ridden bikes of 2020. Preperation for any future lockdowns does not need to emphasize bike rotation or renewal.

##### Bike Distribution Comparison
- One of the most important decisions to make to facilitate ridership during periods of lockdown is to distribute bikes to start stations that see increases during lockdowns. Pershing Square North is our busiest station for nearly every year prior to 2020, but we see a sharp decline in rides starting from that station during lockdown. In the 1.5 month period during the 2020 timeframe, over 15,700 rides started from Pershing Square North, whereas the remaining 3.5 months only saw 9,500 rides begin from there. Conversely, 7,500 rides were began from 12 Ave & W 40 during the 1.5 initial months pre-lockdown, but over 27,100 rides were started from there during the lockdown and recovery period. We should therefore redistribute bikes amongst the stations that saw a larger share of ridership and investigate into the services/businesses in those areas so as to redistribute bikes to similarly situated start stations.

##### Recovery Trends
- Though lockdown slowdowns may be harrowing, recovery patterns in the late spring/summer period are positive and show quick rebounds. Recovery trends vary across various demographic groups. We see the quickest recovery to prelockdown patterns in males, individuals in their 20s/30s, and subscribers. Outreach and advertising should target female riders and individuals in their 40s/50s, as these two demographics make up a significant proportion of ridership yet are less likely to show ridership behavior recoveries to prelockdown levels. We should still encourage subscription participation, as that would likely facilitate quicker recoveries among users.

##### Busiest Stations, both Starting and Ending
- The highest traffic starting and ending stations fluctuate very little during typical timeframes. These linked datasets illustrate an increased volitility in bike traffic during the lockdown period (see March-May 2020). The busiest starting stations in 2019 tend to be distributed on the west side of Manhattan, whereas 2020 shows more even distribution in Manhattan. 2020 follows a similar trend, with many of the busiest starting stations also being the busiest ending stations

### Conclusion
The usefulness of this dataset is in its ability to inform how we handle potential (and likely) future pandemic lockdowns, as well as anticipate how ridership may recover. In summation:
- Bike wear is heavily reduced during lockdowns. We can rotate through less resources and move our attention to other areas of logistics.
- Bike distribution becomes incredibly important during lockdowns. We need to investigate the features of heavy traffic stations during lockdown so that we can redistribute resources to neighborhoods that need access to bikes during these periods.
- Recovery was rapid, with a general return to normalcy within several months of ending lockdown. Young male subscribers drove much of that recovery, and we can target other significant demographics to encourage even faster recovery pace (middle aged females who are not yet subscribers, for example).
