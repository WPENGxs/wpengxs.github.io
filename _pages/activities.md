---
layout: page
permalink: /activities/
title: Activities
description: This is activities
nav: true
nav_order: 3

# profile:
#   align: left # right
#   image: 
#   image_circular: false # crops the image to make it circular
#   address: >

activities: true

tags: ['test', 'ccf']
---

{% for activity in site.activities %}
  <h2>{{ activities.name }} - {{ activities.date }}</h2>
  <p>{{ activities.content | markdownify }}</p>
{% endfor %}