---
title: "Home"
layout: textlay
excerpt: "Prateek Jain"
sitemap: false
permalink: /news.html
---

# News

{% for article in site.data.news_mlo %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
