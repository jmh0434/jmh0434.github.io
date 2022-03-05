---
title: "APP"
layout: archive
pemalink: /categories/app
author_profile: true
sidebar_main: true
---

{% assign posts = site.categories.app %}
{% for post in posts %} {% include archive-single2.html type= page.entries_layout %} {% endfor %}
