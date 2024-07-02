---
permalink: /
title: "About Me | Weihong Xu"
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>
{% include_relative includes/intro.md %}

<span class='anchor' id='news'></span>
{% include_relative includes/news.md %}

<span class='anchor' id='educations'></span>
{% include_relative includes/edu.md %}

<span class='anchor' id='highlight-pubs'></span>
{% include_relative includes/highlight_pubs.md %}

<span class='anchor' id='full-pubs'></span>
{% include_relative includes/full_pubs.md %}
