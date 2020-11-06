---
layout: archive
title: "Selected Publications"
permalink: /publications/
---

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
