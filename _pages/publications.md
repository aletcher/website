---
layout: page
permalink: /publications/
title: publications
description: Publications in reversed chronological order.
years: [2021, 2020, 2019, 2018]
types: [papers, theses]
---

<h2 class="publications">{{"papers"}}</h2>
{% for y in page.years %}
  <h3 class="year">{{y}}</h3>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

<h2 class="publications">{{"theses"}}</h2>
{% bibliography -f theses %}
