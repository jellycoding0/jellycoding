---
title: "gitblog title"
layout: archive
permalink: {{ site.baseurl }}/categories/git/
# permalink: /jellycoding/categories/blog
author_profile: true
sidebar_main: true
---

{% assign posts = site.baseurl.categories.gitblog %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}