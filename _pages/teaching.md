---
layout: archive
title: "Courses taught"
permalink: /teaching/
author_profile: true
---

{% include base_path %}

<!-- ## Teaching interests
Tyler’s teaching interests are centered in physical chemistry, including thermodynamics and statistical mechanics, quantum mechanics, and spectroscopy. He and the associated labs. He is revising the upper-level physical chemistry labs at William & Mary to incorporate more student-faculty interaction. -->

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
