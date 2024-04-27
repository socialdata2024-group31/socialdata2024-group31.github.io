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
    <iframe id="crimeTimeline" src="/assets/images/timeline/timeline.html" scrolling="no" style="min-height: 1748px; width: 1240px; margin: 0 auto; display: block; border: none; position: absolute; left: -255px;" onload="adjustIframeHeight()"></iframe>
</div>

During the Covid-19 pandemic, crime rates were lower than in 2019. By the end of 2022, they had almost returned to pre-pandemic levels. This suggests that as restrictions eased, some criminal activities rebounded, indicating the impact of social and economic factors on crime rates.
<iframe src="/assets/images/Plot/crime_counts.html" width="100%" height="610"></iframe>
Taking a deeper look into focused crime categories, showed interesting trends.

<img src="/assets/images/plot.png" style="width: 100%;" >
## References

1. [George Floyd protests in NYC turn violent: Officers punched, pelted, more than 40 people arrested](https://www.foxnews.com/us/george-floyd-protests-nyc-turn-violent-several-arrested)
2. [Protests in George Floyd's death turn violent in Brooklyn; cops injured, hundreds arrested](https://abc7ny.com/foley-square-protest-gwen-carr-union-eric-garner/6218834/)
3. [Violence in the Big Apple throughout the COVID-19 pandemic: A borough-specific analysis](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9095435/)
