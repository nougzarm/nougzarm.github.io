---
layout: archive
title: "Projets"
permalink: /projets/
author_profile: true
---

Sur cette page vous trouverez une partie des projets que j'ai pu réaliser. Une liste plus complète figure sur mon CV, visible dans la section [CV](../cv).

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.projets reversed %}
  {% include archive-single.html %}
{% endfor %}