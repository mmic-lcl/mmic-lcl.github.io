---
layout: archive
title: "科研训练计划"
permalink: /training/
author_profile: true
---

{% include base_path %}



{% for post in site.training reversed %}
  {% include archive-single.html %}
{% endfor %}
