---
layout: page
permalink: /research/
title: Research
description: 
years: [Ongoing, 2021, 2020, 2019]
nav: true
nav_order: 2
---

<div class="Research">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
