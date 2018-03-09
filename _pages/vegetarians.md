---
layout: archive
title: "Vegan & Vegetarian Recipes"
permalink: /vegetarians/
---

{% for post in site.vegetarians limit: 5 %}
  {% include archive-single.html %}
{% endfor %}
