---
layout: default
title: Projects
---
{% for post in site.posts %}
{% if post.tags contains "project" %}
{% if post.logo_options %}
[![{{ post.title }}]({{ post.logo }}){:{{ post.logo_options }}} ]({{ post.url }}){: style=left, {{ post.logo_options }} }
{: style="text-align: center; " }
{% else %}
[![{{ post.title }}]({{ post.logo }})]({{ post.url }})
{: style="text-align: center; " }
{% endif %}
{% endif %}
{% endfor %}
