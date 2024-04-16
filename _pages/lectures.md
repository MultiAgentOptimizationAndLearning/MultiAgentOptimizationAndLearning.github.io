---
layout: page
permalink: /lectures/
title: lectures
description:
years: [Day 1, Day 2, Day 3]
nav: true
nav_order: 2
---
Copyright (c) 2024 Stefan Vlaski and Ali H. Sayed.

The material on this website is made available to attendees of the IEEE ICASSP 2024 Short Course ``Multi-Agent Optimization and Learning'' for personal use. It may not be copied, modified, or distributed without written consent by the instructors.

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f lectures -q @*[year={{y}}]* %}
{% endfor %}

</div>
