---
layout: archive
title: "Blog"
permalink: /blog/
related: true
author_profile: true
feature_row2:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "Join Our Discord Community"
    title: "Join Our Discord Community"
    excerpt: 'Looking for a community to join? Checkout our Discord'
    url: "https://join.deviantbound.com"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% for post in site.posts limit: 5 %}
  {% include archive-single.html %}
{% endfor %}

{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_row2" type="left" %}