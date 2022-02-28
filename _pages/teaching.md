---
layout: archive
title: "Courses taught"
permalink: /teaching/
author: tyler
author_profile: true
---

{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}

Tyler maintains LaTeX files of many equations used in physical chemistry. You can access them at his [GitHub repository](https://github.com/tkmeldrum/pchem_equations).
