---
layout: default
title: Moments
permalink: /life/
nav: true
display_categories: [life]
---

{%- assign sorted_projects = site.life | sort: "date" -%}
  <!-- Generate cards for each project -->
  {% include timeline_moments.html %}
  <!-- https://codepen.io/brady_wright/pen/NNOvrW?editors=1000 -->