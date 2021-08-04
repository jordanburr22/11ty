---
title: Welcome to the Blog!
permalink: /
tags: no
---

{% for blog in collections.blog %}
- [{{blog.data.title}}]({{blog.url}})
{% endfor %}

You should read it!