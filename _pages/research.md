---
layout: splash
title: "Research in the Meldrumlab"
permalink: /research/
author: meldrumlab
author_profile: false

header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: foo-bar-identity.jpg
  caption:
  excerpt: ""

intro:
  - excerpt: 'Magnetic resonance, on materials, with students'

feature_row1:
  - image_path: foo-bar-identity.jpg
    alt: "placeholder image 2"
    title: "Materials"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row2:
  - image_path: greenGold.jpg
    alt: "placeholder image 2"
    title: "Cultural Heritage"
    excerpt: 'Work on objects of cultural heritage from a materials perspective'
    url: "#test-link"

feature_row3:
  - image_path: foo-bar-identity.jpg
    alt: "placeholder image 2"
    title: "Methods"
    excerpt: 'Software and hardware methods for improved single-sided NMR'
    url: "/research/methods"
---

{% include base_path %}

{% include feature_row id="feature_row1" type="left" %}

{% include feature_row id="feature_row2" type="right" %}

{% include feature_row id="feature_row3" type="center" %}
