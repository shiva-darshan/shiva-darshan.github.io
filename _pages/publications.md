---
layout: archive
title: "Publications and Preprints"
permalink: /publications/
author_profile: true
---


You can also find my articles and preprints on the <u><a href="{{author.arxiv}}" >ArXiv</a></u> or on <u><a href="{{author.googlescholar}}">Google Scholar</a>.</u>


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
