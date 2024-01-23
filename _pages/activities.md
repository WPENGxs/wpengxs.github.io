---
layout: page # activities
permalink: /activities/
title: Activities
description: This is activities
nav: true
nav_order: 3
---

<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>