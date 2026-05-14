---
layout: archive
title: "Projets"
permalink: /projets/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.projets reversed %}
  {% include archive-single.html %}
{% endfor %}

<sup>*</sup> Equal authorship