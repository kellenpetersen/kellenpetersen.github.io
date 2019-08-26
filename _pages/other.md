---
layout: archive
title: "Other"
permalink: /other/
author_profile: true
---

Here are some research projects I've done as undergraduate and master student. They were all written in french.

{% include base_path %}

{% for post in site.other reversed %}
  {% include archive-single.html %}
{% endfor %}
