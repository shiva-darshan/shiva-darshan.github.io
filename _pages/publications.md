---
layout: archive
title: "Publications and Preprints"
permalink: /publications/
author_profile: true
---


You can also find my articles and preprints on the <a href="https://arxiv.org/a/darshan_s_1.html" >ArXiv</a> or on <a href="https://scholar.google.com/citations?user=lLFYA8wAAAAJ">Google Scholar</a>.o


{% include base_path %}

{% for post in site.preprints reversed %}
  {% include archive-single.html %}
{% endfor %}
