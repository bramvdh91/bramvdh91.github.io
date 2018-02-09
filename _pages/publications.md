---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Please check [google scholar](https://scholar.google.be/citations?user=DoLXRvAAAAAJ&hl=nl)
for a complete list of publications.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}
