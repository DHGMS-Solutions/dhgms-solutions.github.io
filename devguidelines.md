---
title: Development Guidelines
layout: default
---

<h1>Development Guidelines</h1>

<ul>
{% for guideline in site.data.devguidelines %}
<li><a href="#{{ guideline.id }}"></a>{{ guideline.rule }}</li>
{% endfor %}
</ul>
