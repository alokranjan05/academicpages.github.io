---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
{% include base_path %}

## Publications
{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}

## Working Papers
{% for post in site.workingpapers reversed %}
  {% include archive-single.html %}
{% endfor %}

## Work in Progress
{% assign ordered_pages = site.research | sort:"order_number" %}
{% for post in ordered_pages %}
  {% include archive-single.html %}
{% endfor %}
