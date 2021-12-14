---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% include base_path %}

### Teaching Interests
Tyler’s teaching interests are centered in physical chemistry, specifically thermodynamics and statistical mechanics. His usual courses include CHEM 103 (general chemistry), CHEM 302 (physical chemistry), CHEM 341 (physical and analytical chemistry for life sciences), and the associated labs. He is revising the upper-level physical chemistry labs at William & Mary to incorporate more student-faculty interaction.

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
