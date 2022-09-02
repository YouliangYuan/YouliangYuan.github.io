---
layout: archive
title: "Selected/Recent Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

\* Corresponding Author

Complete list: \[[Google Scholar](https://scholar.google.com/citations?view_op=list_works&hl=en&user=cd-wSAsAAAAJ&hl=en)\]
