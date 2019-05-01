---
title: Contributors
---

As a class, we have all contributed to this site equally.

{% for contributor in site.contributors %}
{{contributor.name}}<p>
{% endfor %}
