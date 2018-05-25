---
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---

You can also see a [map](/talkmap.html) of all the places where I've given a talk.

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
