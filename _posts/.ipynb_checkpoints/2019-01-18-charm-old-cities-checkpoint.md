---
layout: post
title:  "The Narcotics crime trend in San Francisco"
author: william
categories: [ Crime, Narcotics, Police]
image: assets/images/home.jpg
tags: [sticky]
---
Our journalists have for some time followed the crime rate related to Narcotics and Drugs in San Francisco. Using the San Francisco Police Department database, they have found some interesting trends and insights, that would surely interest our readers.

First, we wanted to see if the trend is on the rise od declining. To visualize that, we used the calendar plot. It showed that the rate of NARCOTIC/DRUG related crimes reduced dramatically circa 2010 to 2013. At first thought, we found that there has been a [new legislative][new-legislative] making the crime of possession of 1 ounce of cannabis from misdemeanor to a civil infraction . But that was only related to cannabis what about other narcotics, the crimes related to them also reduced as cannabis makes only a part of all the crimes in the DRUG/NARCOTIC category. And also in 2016 the usage and sale of cannabis  for recreational purposes has been [legalized in the state of California][legalized-in-the-state-of-California].

As the USA coined the term War on drugs and has been dealing with these issues for very long time, we wanted to know how did the San Francisco reduced the crime related activity in this category.

![walking]({{ site.baseurl }}/assets/images/my_plot.png)
Figure 1:  Calendar plot of Drug and Narcotic related crimes from 2003 to 2017.


[new-legislative]:  https://www.lao.ca.gov/ballot/2010/19_11_2010.pdf

[legalized-in-the-state-of-California]: https://en.wikipedia.org/wiki/Cannabis_in_California


Using an interactive visualization, we plotted certain Drug and related related crime using their description. They were chosen based on their occurence of at least 1000 occurences in the analyzed timeframe. We ended up with 18 categories that were plotted againts years, to see how much dramatically did the rate reduce. 

First we have to say there are three groups, crime of possession, means mainly for personal use if the quantity of drug is below the certain threshold, crime of possession for sale, the quantity of drug is above the certain threshold and crime of selling the drug, meaning the culprit was caught in an act.

From the visualization most of the possession drug related crimes decreased, after hitting peak around the 2009 and 2010, except the Possession of meth-amphetamine, that started to decrease after reaching its peak 2014. In 2014 California [Proposition 47][Proposition-47] voted on referendum making certain felonies into misdemeanors, one of them was personal use of drugs, if the quantity was below certain threshold. The proposition was introduced to tackle overcrowding of prisons, as The United States of America possesses [the most significant incarcerated population] [the-most-significant-incarcerated-population] and it would also allow to rellocate the funds, that would be used to prosecute them for different endeavours like rehabilitation facilities and such. Of course, that doesn't mean that the crimes would no longer be criminal offences as it is regarding only non-violent drug possession. 

The Proposition 47 is part of the decriminalization approach, that wants to ease the punitive actions as most of the arrested people, that was 82% in 2013 were only [arrested for possession][arrested-for-possession]. Decriminalization, removing criminal penalties for drug offenses, and prioritizing treatment and harm reduction, offer a more effective approach to addressing drug misuse and improving public safety. Countries with less punitive drug policies show no significant rise in drug use, harm, or crime compared to stricter nations. A World Health Organization study highlights that despite punitive measures, the U.S. exhibits the highest lifetime drug use rates, indicating minimal impact of [decriminalization on usage rates][decriminalization-on-usage-rates]. Crimes regarding possession for sale and sale also reduced except regarding possession of heron and meth-amphetamine.

From what we found, the lessened crime rate was not in result of more effective policing strategy, but handling the drug related crimes in a different way, that treats the offenders more humanely and tries to rehabilitate them.
<iframe src="{{ site.baseurl }}/assets/images/bokeh/bokeh.html"
    sandbox="allow-same-origin allow-scripts"
    width="140%"
    height="700"
    scrolling="no"
    seamless="seamless"
    frameborder="0">
</iframe>


[Proposition-47]:https://en.wikipedia.org/wiki/2014_California_Proposition_47
[the-most-significant-incarcerated-population]:https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://www.statista.com/statistics/262962/countries-with-the-most-prisoners-per-100-000-inhabitants/&ved=2ahUKEwiQxNyoqo-FAxWl0gIHHcxrAJwQFnoECBAQAw&usg=AOvVaw0bsZ-uIW2C1I7ez4CWgQ80
[arrested-for-possession]:https://www.unodc.org/documents/ungass2016/Contributions/Civil/DrugPolicyAlliance/DPA_Fact_Sheet_Approaches_to_Decriminalization_Feb2015_1.pdf
[decriminalization-on-usage-rates]: https://pubmed.ncbi.nlm.nih.gov/18597549/


