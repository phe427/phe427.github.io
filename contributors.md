---
title: Contributors
---

As a class, we have all contributed to this site equally.

{% for contributor in site.data.contributors %}
- <b>{{ contributor.name }}</b> ({{contributor.role}})
{% endfor %}
