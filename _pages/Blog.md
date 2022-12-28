---
layout: category
taxonomy: Blog
entires_layout: grid
title: Blog Title for category
permalink: "/blog/"
author_profile: true
---

{% assign posts = site.categories.Cpp %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}