---
title: Contributors
---

{% assign sorted_contributors = site.contributors | sort: 'name' %}

{% for contributor in sorted_contributors %}
  {% include contributor.html %}
{% endfor %}