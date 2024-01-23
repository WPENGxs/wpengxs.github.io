---
layout: activities
permalink: /activities/
title: Activities
description: This is activities
nav: true
nav_order: 3

profile:
  align: left # right
  image: 
  image_circular: false # crops the image to make it circular
  address: >

pagination:
  enabled: true
  collection: posts
  permalink: /page/:num/
  per_page: 5
  sort_field: date
  sort_reverse: true
  trail:
    before: 1 # The number of links before the current page
    after: 3  # The number of links after the current page

news: false  # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false  # includes social icons at the bottom of the page

tags: ['test', 'ccf']
---
