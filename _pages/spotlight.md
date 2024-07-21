---
layout: archive
title: "Spotlight"
permalink: /spotlight/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}


{% for post in site.spotlight reversed %}
  {% include archive-single.html %}
{% endfor %}




**Spotlight Projects**
- <a href="https://github.com/RobustNLP/CipherChat"> <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/RobustNLP/CipherChat?label=Github%20Stars&style=social"> </a>: [CipherChat](https://github.com/RobustNLP/CipherChat)    

