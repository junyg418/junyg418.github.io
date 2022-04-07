---
title: "Python 관련"
permalink: /categories/python/
layout: category
author_profile: true
taxonomy: python
---

Python 관련이에요.

{% assign posts = site.categories.python %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}