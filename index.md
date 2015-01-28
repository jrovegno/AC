---
title: Indice
layout: index
---

# Propuesta Nueva Constitución

<ul>
{% for page in site.pages %}
    {% if page.title != 'Indice' %}
    <li><a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a></li>
    {% endif %}
{% endfor %}  <!-- page -->
</ul>

