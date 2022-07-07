---
layout: single
title: "Publications"
permalink: /publications/
author: meldrumlab
author_profile: true
---

{% include base_path %}

{% if author.googlescholar %}
  You can also find our articles on <a href="{{author.googlescholar}}"> Google Scholar</a>.
{% endif %}

<u>Underlined names</u> indicate undergraduate student co-authors.
<b>Boldface names</b> indicate graduate student co-authors.

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
