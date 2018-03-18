---
layout: default
title: Inclusive Design Tips
---

<ol>
{% for tip in site.tips %}
<li>
  <h3><a href="{{ tip.url }}">{{ tip.title }}</a></h3>
  <p>{{ tip.why }}</p>
</li>
{% endfor %}
</ol>
