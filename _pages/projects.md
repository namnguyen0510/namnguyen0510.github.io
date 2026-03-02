---
title: "Projects"
layout: archive
permalink: /projects/
author_profile: true
---

{% assign projects = site.projects | sort: 'date' | reverse %}
{% for post in projects %}
  {% include archive-single.html %}
{% endfor %}

