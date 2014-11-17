---
title: Development States
layout: default
---

<h1>Development States</h1>

{% for devstate in site.data.devstates %}
<a href="#{{ devstate.name }}"></a>
<h2>{{ devstate.longname }}</h2>
<p>{{ devstate.description }}</p>
{% endfor %}
