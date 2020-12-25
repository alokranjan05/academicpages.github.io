---
layout: archive
title: "Working Papers"
permalink: /workingpapers/
author_profile: true
---
{% include base_path %}

## Working Papers
{% for post in site.workingpapers reversed %}
  {% include archive-single.html %}
{% endfor %}
