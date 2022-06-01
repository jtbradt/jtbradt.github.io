---
layout: page
permalink: /research/
title: Research
description: 
years:
nav: true
nav_order: 2
---
<style>
.myDiv {
    margin: 30px 0px 30px 0px;
}
</style>


<div class="publications">

<!--
{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}} & abbr={{"Working Paper"}}]* %}
{% endfor %}
-->

<div class="myDiv">
<h2> In Progress </h2>
{% bibliography -f papers -q @*[type=In Progress]* %}
</div>

<div class="myDiv">
<h2> Publications </h2>
{% bibliography -f papers -q @*[type=Publication]* %}
</div>

<div class="myDiv">
<h2> Working Papers </h2>
{% bibliography -f papers -q @*[type=Working Papers]* %}
</div>

</div>
