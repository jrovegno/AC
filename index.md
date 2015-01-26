---
title: Indice
layout: default
---

# Propuesta Nueva Constitución

<ul>
{% for page in site.pages %}
<li><a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a></li>
{% endfor %}  <!-- page -->
</ul>

{% for page in site.pages %}
    {% if page.flag == 'capitulos' %}
    <li><a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a></li>
    {% endif %}
{% endfor %}
