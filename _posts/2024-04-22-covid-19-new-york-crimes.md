---
layout: post
title: "A Look at New York City Crime During the Pandemic"
categories: [Social data analysis]
image: assets/images/covid19.webp
---

<script>
    function adjustIframeHeight() {
        var iframe = document.getElementById("crimeTimeline");
        var iframeHeight = iframe.contentWindow.document.body.scrollHeight;
        iframe.style.height = iframeHeight + 28 + "px";
        var iframeContainer = document.getElementById("iframeContainer");
        iframeContainer.style.height = iframeHeight + 28 + "px";
    }
</script>

The Covid-19 pandemic changed urban life in New York, influencing everything from daily routines to crime rates. Our data story focuses on how crime trends shifted during the pandemic, beginning with a timeline that recaps key events and their effects on crime in the city.

<div id="iframeContainer" style="position: relative; width: 100%; text-align: center;">
    <iframe id="crimeTimeline" src="/assets/images/timeline/timeline.html" scrolling="no" style="min-height: 3374px; width: 1240px; margin: 0 auto; display: block; border: none; position: absolute; left: -255px;" onload="adjustIframeHeight()"></iframe>
</div>

During the Covid-19 pandemic, crime rates were lower than in 2019. By the end of 2022, they had almost returned to pre-pandemic levels. This suggests that as restrictions eased, some criminal activities rebounded, indicating the impact of social and economic factors on crime rates. The spike during May 2020 is noticeable but it still wasn't comparable to pre-pandemic numbers.

<iframe src="/assets/images/Plot/crime_counts.html" width="100%" height="610"></iframe>
Taking a deeper look into focused crime categories, showed interesting trends. In the year 2020 most of the investigated crimes increased quite noticeably, the most of was burglary, public order offenses and dangerous weapons.

As seen in the previous plot the majority of the increases were also not on the same level as pre-pandemic times. The noticeable exception is Burglary of May 2020.

What can be also seen is that for the pre and post pandemic crime occurences, the crime rates for some of them did return to the same stage and evened out for example Theft and Assault. But some decreases dramatically staying on the same number of occurences like during Covid restrictions. Those would be Alcohol and Drug related offenses.

<img src="/assets/images/plot.png" style="width: 100%;" >
    To see closely how restricting and opening affected the crime rate, the next plot will show the year 2020 in weekly segments. In New York state of emergency was declared in the 10th week [[9]](https://www.investopedia.com/historical-timeline-of-covid-19-in-new-york-city-5071986), but evident decrease is first seen on 12th week as that was the time when schools, bars and restaurants were closed and also all the non-essential workers had to stay home. This only lasts until around the 16th week as from that time there is a discernible increase that only went up and peaked during the protests of George Floyd's death. This rise could be explained by economic instability as during lockdown many businesses were closed, which made them an easy target for break-ins. The burglary rate went up by 32 percent [[10]](https://www.politico.com/states/new-york/albany/story/2020/05/04/nyc-crime-rate-drops-during-coronavirus-but-commercial-break-ins-spike-1281986).
<img src="/assets/images/bar2020.png" style="width: 100%;" >
Delving into demographics like race, gender and age to see if any interesting trends will pop up. the african-american population leads in all four years, but in 2020 there is an significant decrease in amount of crimes comitted through the whole year. Such thing cannot be explained easily, why do african-american population tends to commit more crimes, due to the historical and socio-economical reasons, but one thing is obvious. There is an evident disparity of wealth between white and african-american households. White New Yorkers have a median household net worth of $276,900, almost 15 times (or 1400 percent) higher than the $18,870 median household net worth of Black New Yorkers [[11]](https://comptroller.nyc.gov/reports/the-racial-wealth-gap-in-new-york/).
<img src="/assets/images/monthly_trends.png" style="width: 100%;" >
To probe more deeply, into the issue, they were grouped into our chosen focus categories to see real distribution in races and then also differentiated in gender, all for year 2020. The White Hispanic group stood out as the top ethnicity for alcohol-related crimes in the year 2020. One interesting thing to note would be the increase in Fraud related crimes by the second half of the year, as the pandemic affected many economically and socially. With the Coronavirus Aid, Relief and Economic Security (CARES) Act, that should have offered help to the people who needed it the most, there were many individuals who illegally obtained help, when they didn't need it or deserve it. In the paper by Zhang et al (2022), where they studied the connection of increasing Covid-19 cases and Frauds [[12]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9707139/). Fraud tends to thrive during downturns and crises, both of which are occurring with the COVID-19 pandemic. 
<img src="/assets/images/monthly_trends_race.png" style="width: 100%;" >
When comparing between the two genders, there isn't much of a surprise as more crimes are comitted by men than women. One surprising thing aspect could be that in the figure of crimes comitted by women, more Fraudulent crimes were comitted by the Asian/Pacific Islanders group, but as the occurence of the crime was still low, it would seem it is not as important.
<div style="display: flex; justify-content: space-between;">
    <img src="/assets/images/monthly_trends_men.png" style="width: 50%;" >
    <img src="/assets/images/monthly_trends_women.png" style="width: 50%;" >
</div>
Another demographic data observed was the age of the criminals, that showed that the majority of crimes were comitter by people between the age 25-44, which makes sense. The two other age groups of concern are 18-24 and 45-64.
<iframe src="/assets/images/crime_heatmap.html" width="100%" height="610"></iframe>
After properly exploring the data, what was found interesting were the Fraudulent crimes. It is not a crime one would think would be of concern, but as people were isolated, they were more easy to fall into schemes of seemingly friendly strangers and as mentioned before people would misuse the help offered by the CARES Act and abuse it.

From the data it cannot be confirmed which type of fraudulent act it is, but it is seen that during time of COVID-19 the problem only grew larger as can be observed in the plot. The average of 2019 shown in the plot, has been overcame in 2021 many times.

In the first 9 months of 2020, Americans have reporterdly lost over 145 million dollars [[13]](https://www.nytimes.com/2020/09/23/us/coronavirus-scams-ftc-reports.html). People fell to scams related to fake medicine, covid tests and more, as people become more vulnerable in stressful situations. For the crimes were people defrauded the government, as about 5 trillion dollars have been provided and there is no clear estimate of how much money from that was stolen. Some claim its less than 10 billion dollars, some say it could near almost 100 billion dollars [[14]](https://www.nytimes.com/2022/08/16/business/economy/covid-pandemic-fraud.html) [[15]](https://www.nbcnews.com/politics/justice-department/biggest-fraud-generation-looting-covid-relief-program-known-ppp-n1279664). Many call it the largest fraud in U.S. history, most of it will never be recovered and it will take decades of prosecuting to get all the guilty parties behind bars.
<img src="/assets/images/trends_fraud.png" style="width: 100%;" >

## References

1. [George Floyd protests in NYC turn violent: Officers punched, pelted, more than 40 people arrested](https://www.foxnews.com/us/george-floyd-protests-nyc-turn-violent-several-arrested)
2. [Protests in George Floyd's death turn violent in Brooklyn; cops injured, hundreds arrested](https://abc7ny.com/foley-square-protest-gwen-carr-union-eric-garner/6218834/)
3. [Violence in the Big Apple throughout the COVID-19 pandemic: A borough-specific analysis](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9095435/)
4. [Everything We Do and Don’t Know About New York’s Reopening](https://nymag.com/intelligencer/2020/08/when-will-new-york-reopen-phases-and-full-plan-explained.html)
5. [Everything you need to know about Phase 3 reopening plans in NYC](https://www.timeout.com/newyork/news/everything-you-need-to-know-about-phase-3-reopening-plans-in-nyc-070120)
6. [New York City’s Phase 4, Explained](https://www.nytimes.com/2020/07/20/nyregion/nyc-phase-4-reopening-coronavirus.html)
7. [Governor Cuomo Announces COVID-19 Restrictions Lifted as 70% of Adult New Yorkers Have Received First Dose of COVID-19 Vaccine ](https://www.governor.ny.gov/news/governor-cuomo-announces-covid-19-restrictions-lifted-70-adult-new-yorkers-have-received-first)
8. [Governor Cuomo Announces New York City Indoor Dining Will Expand to 75 Percent Capacity Beginning May 7](https://www.governor.ny.gov/news/governor-cuomo-announces-new-york-city-indoor-dining-will-expand-75-percent-capacity-beginning)
9. [A Historical Timeline of COVID-19 in New York City](https://www.investopedia.com/historical-timeline-of-covid-19-in-new-york-city-5071986)
10. [NYC crime rate drops during coronavirus, but commercial break-ins spike](https://www.politico.com/states/new-york/albany/story/2020/05/04/nyc-crime-rate-drops-during-coronavirus-but-commercial-break-ins-spike-1281986)
11. [ The Racial Wealth Gap in New York](https://comptroller.nyc.gov/reports/the-racial-wealth-gap-in-new-york/)
12. [Vulnerability and fraud: evidence from the COVID-19 pandemic](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9707139/)
13. [Americans Have Lost $145 Million to Coronavirus Fraud](https://www.nytimes.com/2020/09/23/us/coronavirus-scams-ftc-reports.html)
14. [Prosecutors Struggle to Catch Up to a Tidal Wave of Pandemic Fraud](https://www.nytimes.com/2022/08/16/business/economy/covid-pandemic-fraud.html)
15. [Biggest fraud in a generation': The looting of the Covid relief plan known as PPP](https://www.nbcnews.com/politics/justice-department/biggest-fraud-generation-looting-covid-relief-program-known-ppp-n1279664)
16. [Cuomo Imposes Tight Virus Rules on Areas Hit by Spikes Across State](https://www.nytimes.com/2020/10/06/nyregion/cuomo-shutdown-coronavirus.html)
17. [Protesters flood NYC to rally against death of George Floyd](https://nypost.com/2020/05/29/protestors-flood-nyc-to-rally-against-death-of-george-floyd/)
18. [A Weekend of Anger and Defiance Across New York City](https://www.newyorker.com/news/our-local-correspondents/a-weekend-of-anger-and-defiance-across-new-york-city-george-floyd-police-protesters)
