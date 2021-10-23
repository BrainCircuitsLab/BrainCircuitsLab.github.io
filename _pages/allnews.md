---
title: "News"
layout: textlay
excerpt: "The BrainCircuits Lab at The University of Texas at Dallas."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
