---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---

{% include base_path %}
  
Talks
======
  {% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}
  
Posters
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  

