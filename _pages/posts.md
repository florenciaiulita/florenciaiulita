---
layout: archive
title: "All my posts"
author_profile: true
excerpt: "A List of all my posts"
permalink: /posts/
---

{% include base_path %}

{% for post in paginator.posts %}
  {% include archive-single.html %}
{% endfor %}

{% include paginator.html %}