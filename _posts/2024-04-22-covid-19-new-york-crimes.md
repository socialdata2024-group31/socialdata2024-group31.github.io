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

How COVID-19 changed crime in New York City.

<div id="iframeContainer" style="position: relative; width: 100%; text-align: center;">
    <iframe id="crimeTimeline" src="/assets/images/timeline/timeline.html" scrolling="no" style="min-height: 1748px; width: 1240px; margin: 0 auto; display: block; border: none; position: absolute; left: -255px;" onload="adjustIframeHeight()"></iframe>
</div>

More blah

## References

1. [George Floyd protests in NYC turn violent: Officers punched, pelted, more than 40 people arrested](https://www.foxnews.com/us/george-floyd-protests-nyc-turn-violent-several-arrested)
2. [Protests in George Floyd's death turn violent in Brooklyn; cops injured, hundreds arrested](https://abc7ny.com/foley-square-protest-gwen-carr-union-eric-garner/6218834/)
