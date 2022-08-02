---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---

You can also find my software on [my GitHub profile](https://github.com/cumbof).

{% include base_path %}

{% for post in site.software reversed %}
  {% include archive-single.html %}
{% endfor %}
