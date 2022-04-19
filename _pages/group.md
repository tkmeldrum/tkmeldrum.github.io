---
layout: archive
title: "Meldrumlab people"
permalink: /group/
author: meldrumlab
author_profile: true
---
<img src="images/group2022.JPG" alt="The Meldrumlab Group, Spring 2022">

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
- Barbara Berrie ([National Gallery of Art; Washington, DC](https://www.nga.gov))
- Gwendoline Fife, René Hoppenbrouwers ([SRAL, Maastricht, The Netherlands](https://www.sral.nl/en))
- [Prof. Ville Telkki (The University of Oulu, Finland)](https://www.oulu.fi/university/researcher/ville-veikko-telkki)
- [Prof. Christian Hilti (Texas A&M University)](https://www.chem.tamu.edu/rgroup/hilty/)
- [Prof. Kristina Keating (Rutgers University)](https://www.keatinggeophysics.org/)
- [Metna, Co. (Lansing, MI)](https://www.metnaco.com)
- [Prof. Daphna Shimon (The Hebrew University of Jerusalem, Israel)](https://shimongroup.huji.ac.il/dr-daphna-shimon)
