---
layout: archive
title: "Research Projects & Software"
permalink: /projects/
author_profile: true
---

{% include base_path %}

Welcome to my software and research portfolio. Below you can explore my open-source aerospace tools, flight simulations, and flight-ready data pipelines. Click on any project card to view its dedicated documentation and source code links.

---

{% for post in site.projects %}
  {% include archive-single.html %}
{% endfor %}