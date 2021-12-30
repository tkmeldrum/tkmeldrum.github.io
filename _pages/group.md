---
layout: archive
title: "Meldrumlab people"
permalink: /group/
author: meldrumlab
author_profile: true
---

{% include base_path %}

{% assign sortedGroup = site.group | sort: 'lastname' %}

{% for post in sortedGroup %}
  {% include group-single.html %}
{% endfor %}

---
## [Group alumni](/pages/alumni)

---

## Collaborators
We are fortunate to work on interdisciplinary projects with fantastic collaborators. Here are a few of our science friends:
- Barbara Berrie (National Gallery of Art; Washington, DC)
- Gwendoline Fife, René Hoppenbrouwers (SRAL, Maastricht, The Netherlands)
- Prof. Ville Telkki (The University of Oulu, Finland)
- Prof. Christian Hilti (Texas A&M University)
- Prof. Kristina Keating (Rutgers University)
- Metna, Co. (Lansing, MI)
- Prof. Daphna Shimon (The Hebrew University of Jerusalem, Israel)
