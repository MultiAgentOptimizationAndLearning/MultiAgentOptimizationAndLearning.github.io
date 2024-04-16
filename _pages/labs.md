---
layout: page
permalink: /labs/
title: labs
description:
years: [Day 1, Day 2, Day 3]
nav: true
nav_order: 3
---
Three labs to complement the three days of lectures. The examples and code are chosen to illustrate some of the key take-aways developed analytically in lectures. No effort has been made to optimize the implementations, and no guarantees are made for its correctness.

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f labs -q @*[year={{y}}]* %}
{% endfor %}

</div>
