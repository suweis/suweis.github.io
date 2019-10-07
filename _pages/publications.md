---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<p> A complete list of my publication can be found <a href="https://scholar.google.it/citations?user=oorpe-wAAAAJ&hl=it"> <u> here </u> </a> or in the ORCID link on the left.
  
<p>You can also see a <u><a href="/publications/collab_network.html">network</a></u> representing all my publications and collaborators.</p>

<!--{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}-->

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
