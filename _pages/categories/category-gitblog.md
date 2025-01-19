---
title: "gitblog title"
layout: archive
permalink: jellycoding/categories/Git-Blog
author_profile: true
sidebar_main: true
---

{% assign posts = site.categories.gitblog %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}