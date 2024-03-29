---
layout: post
title: "The decriminalization of drugs in San Francisco from 2009 to 2017"
categories: [Social data analysis]
image: assets/images/img7.jpg
---

We dive into the San Francisco Police Department's Incident Reports from 2003 to 2017 to investigate the impact of the changes in drug-related policies in 2014 and 2016 on drug-related incidents. It caught our attention that drug-related incidents significantly decreased from 2010 to 2017 when we first used the calendar plot.

<div style="display:flex; justify-content: space-between; align-items: center;">
    <div style="padding-right:40px">
        <p>
        In 2016, new legislation changed the crime of possessing 1 ounce of cannabis from a misdemeanor to a civil infraction<a href="https://www.lao.ca.gov/ballot/2010/19_11_2010.pdf" target="_blank">[7]</a>. But that was only related to cannabis what about other narcotics, the crimes related to them also reduced as cannabis makes only a part of all the crimes in the DRUG/NARCOTIC category. And also in 2016 the usage and sale of cannabis for recreational purposes has been legalized in the state of California<a href="https://en.wikipedia.org/wiki/Cannabis_in_California" target="_blank">[8]</a>.
        </p>
        <p>
        As the USA coined the term War on drugs and has been dealing with these issues for very long time, we wanted to know how did the San Francisco reduced the crime related activity in this category.
        </p>
    </div>
    <div>
        <a href="/assets/images/calendar.png" data-lightbox="example-set" data-title="Drug-related incidents in San Francisco" id="your-custom-id">
            <img src="/assets/images/calendar.png" style="max-width: 370px;" alt="Calendar plot of drug-related incidents in San Francisco">
        </a>
    </div>
</div>

Using the bookeh visualization, we plotted certain Drug and related related crime using their description, we only chose the ones that had at least 1000 occurences in the analyzed timeframe. We ended up with 18 categories that were plotted againts years, to see how much dramatically did the occurence reduce.

First we have to say there are three groups, crime of possession, means mainly for personal use if the quantity of drug is below the certain threshold, crime of possession for sale, the quantity of drug is above the certain threshold and crime of selling the drug, meaning the culprit was caught in an act.

<iframe src="/assets/images/bokeh/bokeh.html" width="100%" height="610"></iframe>

From the visualization most of the possession drug related crimes decreased, after hitting peak around the 2009 and 2010, except the Possession of meth-amphetamine, that started to decrease after reaching its peak 2014. In 2014 California Proposition 47[[3]][3] voted on referendum making certain felonies into misdemeanors, one of them was personal use of drugs, if the quantity was below certain threshold. The proposition was introduced to tackle overcrowding of prisons, as The United States of America possesses the most significant incarcerated population[[4]][4] and it would also allow to rellocate the funds, that would be used to prosecute them for different endeavours like rehabilitation facilities and such. Of course, that doesn't mean that the crimes would no longer be criminal offences as it is regarding only non-violent drug possession.

The Proposition 47 is part of the decriminalization approach, that wants to ease the punitive actions as most of the arrested people, that was 82% in 2013 were only for possession[[5]][5]. Decriminalization, removing criminal penalties for drug offenses, and prioritizing treatment and harm reduction, offer a more effective approach to addressing drug misuse and improving public safety. Countries with less punitive drug policies show no significant rise in drug use, harm, or crime compared to stricter nations. A World Health Organization study highlights that despite punitive measures, the U.S. exhibits the highest lifetime drug use rates, indicating minimal impact of decriminalization on usage rates[[6]][6].Crimes regarding possession for sale and sale also reduced except regarding possession of heron and meth-amphetamine.

Therefore, the overall downtrend in drug-related incidents from 2010 to 2017 was likely the result of changes in drug-related policies, such as the decriminalization of personal use and the total legalization of marijuana in 2016, rather than a sign of a decrease in drug use.

Throughout the years, The Tenderloin has been the city area where most serious crimes are committed, including assault, burglary, gambling, and drug-related incidents. Even from its foundation in the 1800s, it was known as the entertainment district[[1]][1], with its name said to be a pun on the 'tenderloin' steak[[2]][2], as it was an area where police officers could make enough money on the side (from bribes) to afford the more expensive 'filet mignon'.

<iframe src="/assets/figures/drug_narcotic.html" width="100%" height="500" style="border:none"></iframe>

While drug crimes for personal use have been slowly decriminalized from 2014 and onwards, The Tenderloin still remains a hotspot for drug/narcotic incidents. There was a decrease in the final years of 2016 and 2017 when marijuana was legalized for recreational use. During this time, marijuana-related incidents died out throughout the entire city.

So, while these crimes are often organized, the significant shifts in drug policies in 2014 and 2016 do not seem to affect where drug-related incidents occur (such as relocating to different city areas), but rather only the frequency of the incidents. The same goes for other crimes like assaults and burglaries. While they mostly occur in the same city area as drug sales, they are not shifting to other city areas with the decriminalization of drugs.

[1]: https://www.kqed.org/news/11803642/in-a-changing-city-how-does-the-tenderloin-stay-the-same "In a Changing City, How Does the Tenderloin Stay the Same?"
[2]: https://en.wikipedia.org/wiki/Tenderloin,_San_Francisco "Tenderloin, San Francisco"
[3]: https://en.wikipedia.org/wiki/2014_California_Proposition_47 "2014 California Proposition 47"
[4]: https://www.statista.com/statistics/262962/countries-with-the-most-prisoners-per-100-000-inhabitants/ "Countries with the largest number of prisoners per 100,000 of the national population, as of January 2024"
[5]: https://www.unodc.org/documents/ungass2016/Contributions/Civil/DrugPolicyAlliance/DPA_Fact_Sheet_Approaches_to_Decriminalization_Feb2015_1.pdf "Approaches to Decriminalizing Drug Use & Possession"
[6]: https://pubmed.ncbi.nlm.nih.gov/18597549/ "Toward a global view of alcohol, tobacco, cannabis, and cocaine use: findings from the WHO World Mental Health Surveys"
[7]: https://www.lao.ca.gov/ballot/2010/19_11_2010.pdf "Changes California Law to Legalize Marijuana and Allow It to Be Regulated and Taxed. Initiative Statute"
[8]: https://en.wikipedia.org/wiki/Cannabis_in_California "Cannabis in California"

## References

1. [In a Changing City, How Does the Tenderloin Stay the Same?](https://www.kqed.org/news/11803642/in-a-changing-city-how-does-the-tenderloin-stay-the-same)
2. [Tenderloin, San Francisco - Wikipedia](https://en.wikipedia.org/wiki/Tenderloin,_San_Francisco)
3. [2014 California Proposition 47 - Wikipedia](https://en.wikipedia.org/wiki/2014_California_Proposition_47)
4. [Countries with the largest number of prisoners per 100,000 of the national population, as of January 2024 - Statista](https://www.statista.com/statistics/262962/countries-with-the-most-prisoners-per-100-000-inhabitants/)
5. [Approaches to Decriminalizing Drug Use & Possession - UNODC](https://www.unodc.org/documents/ungass2016/Contributions/Civil/DrugPolicyAlliance/DPA_Fact_Sheet_Approaches_to_Decriminalization_Feb2015_1.pdf)
6. [Toward a global view of alcohol, tobacco, cannabis, and cocaine use: findings from the WHO World Mental Health Surveys - PubMed](https://pubmed.ncbi.nlm.nih.gov/18597549/)
7. [Changes California Law to Legalize Marijuana and Allow It to Be Regulated and Taxed. Initiative Statute - LAO California](https://www.lao.ca.gov/ballot/2010/19_11_2010.pdf)
8. [Cannabis in California - Wikipedia](https://en.wikipedia.org/wiki/Cannabis_in_California)
