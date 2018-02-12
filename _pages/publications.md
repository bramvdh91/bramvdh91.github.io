---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

This page only shows peer-reviewed articles published in international journals. Please check __[ResearchGate](https://www.researchgate.net/profile/Bram_Van_Der_Heijde)__ or __[Google Scholar](https://scholar.google.be/citations?user=DoLXRvAAAAAJ&hl=nl)__ for a complete list of publications, including contributions at conferences.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}
