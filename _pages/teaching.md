---
layout: archive
title: ""
permalink: /teaching/
author_profile: false
---

{% include base_path %}

New York University (Center for Data Science)
======
Causal Inference

Linear Regression Models

Survey in Data Science

University of Chicago (Economics)
======
{% for post in site.teaching reversed %}
  {% include archive-single-teaching.html %}
{% endfor %}
