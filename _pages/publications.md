---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<p>You can also see a <u><a href="/publications/collab_network.html">network</a></u> representing all my publications and collaborators.</p>

<!--{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}-->

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
