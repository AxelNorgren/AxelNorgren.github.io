---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% include base_path %}

{% assign teaching = site.teaching | sort: 'date' | reverse %}
{% for post in teaching %}
  {% include archive-single.html %}
{% endfor %}
