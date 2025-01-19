---
title: "gitblog title"
layout: archive
permalink: categories/gitblog
author_profile: true
sidebar_main: true
---

{% raw %}
{% assign posts = site.categories.Cpp %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}
{% endraw %}