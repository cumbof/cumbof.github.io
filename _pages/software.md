---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---

{% if author.github %}
  You can also find my softwares on <u><a href="https://github.com/{{author.github}}">my GitHub profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.software reversed %}
  {% include archive-single.html %}
{% endfor %}
