---
layout: archive
permalink: /blog/
header:
  overlay_image: /assets/images/travel_cover.jpg
  overlay_filter: 0.5
  caption: "Photo credit: Tarka Wilcox"
  excerpt: "A food and travel blog for the sustainably minded."
feature_row:
  - image_path: assets/images/biking01.jpg
    alt: "biking in Colorado"
    title: "Biking through the Aspens in Colorado"
    excerpt: "Sample text will go here."
feature_row2:
  - image_path: assets/images/mushrooms02.jpg
    alt: "Sample title 2"
    title: "Morel Mushrooms"
    excerpt: "Just my luck, morels at my workplace."
feature_row3:
  - image_path: assets/images/landscape01.jpg
    alt: "Hiking in Taiwan"
    title: "Inspired by Taiwan Landscapes"
    excerpt: "Sample text will go here."
feature_row4:
  - image_path: assets/images/biking02.jpg
    alt: "Mountain biking in Utah"
    title: "Shredding it in Moab"
    excerpt: "Sample text will go here."
---
{% for post in site.posts limit: 5 %}
  {% include archive-single.html %}
{% endfor %}

{% include feature_row id="feature_row" type="left" %}

{% include feature_row id="feature_row2" type="right" %}

{% include feature_row id="feature_row3" type="left" %}

{% include feature_row id="feature_row4" type="right" %}
