---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
You can also find my articles on [Google Schoalr](https://scholar.google.com/citations?user=rK6aw6MAAAAJ&hl=en)
---


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
