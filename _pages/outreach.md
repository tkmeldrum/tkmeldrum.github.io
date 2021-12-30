---
layout: archive
title: "Outreach"
permalink: /outreach/
author: proftyler
author_profile: true
---

{% include base_path %}

Tyler values exposure to science at an early age. As *Professor Tyler,* he designs programs that he presents at the [Williamsburg Regional Library;](https://www.wrl.org) these programs help children understand science and, more importantly, get excited about it. Some of his programs are described below.

{% include image-gallery.html folder="/images/outreach/" %}

{% for post in site.outreach %}
  {% include archive-single.html %}
{% endfor %}
