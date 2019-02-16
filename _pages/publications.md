---
layout: page
permalink: /publications/
title: Publications
description:
years: [2018]
---

As a freshman in the fields of AI, I do not have a lot of publications at the moment, but I am going to add some to the collection in the upcoming year.


{% for y in page.years %}
  <h3 class="year">{{y}}</h3>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}
