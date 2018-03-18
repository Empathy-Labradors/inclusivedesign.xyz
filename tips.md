---
layout: default
title: Inclusive Design Tips
---

<ol>
{% for tip in site.tips %}
<li>
  <h3><a class="tip-{{ tip.category }}" href="{{ tip.url }}">{{ tip.title }}</a></h3>
  <p>{{ tip.why }}</p>
</li>
{% endfor %}
</ol>
