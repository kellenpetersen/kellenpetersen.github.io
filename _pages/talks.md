---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---

{% include base_path %}
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Posters
======
  <ul>{% for post in site.posters reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
  {% for post in site.awards reversed %}
  {% include archive-single.html %}
{% endfor %}
