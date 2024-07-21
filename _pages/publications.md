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



## Projects
- <a href="https://github.com/RobustNLP/CipherChat"> <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/RobustNLP/CipherChat?label=Github%20Stars&style=social"> </a>: [CipherChat](https://github.com/RobustNLP/CipherChat)    

- <a href="https://github.com/RobustNLP/DeRTa"> <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/RobustNLP/DeRTa?label=Github%20Stars&style=social"> </a>: [DeRTa](https://github.com/RobustNLP/DeRTa)    

Complete list: \[[Google Scholar](https://scholar.google.com/citations?view_op=list_works&hl=en&user=cd-wSAsAAAAJ&hl=en)\]
