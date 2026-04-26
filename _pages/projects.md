---
layout: archive
title: "Featured Projects"
permalink: /projects/
author_profile: true
---

## Environmental Intelligence
I build physics-informed sensing systems for environmental intelligence using emerging modalities such as RF, metasurfaces, UWB radar, mmWave sensing, and multimodal learning. My work focuses on translating complex environmental signals into accessible and actionable information for real-world applications such as water quality monitoring, soil sensing, and intelligent agriculture.

{% assign sorted_projects = site.portfolio | sort: 'order' %}

{% for post in sorted_projects %}
  {% if post.category == "Environmental Intelligence" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
---

## AI-Systems
I develop robust and efficient machine learning systems for real-world deployment. My research focuses on learning under missing, delayed, or heterogeneous data, with an emphasis on cross-modality inference, representation learning, and adaptive intelligence in resource-constrained environments.
{% for post in site.portfolio %}
  {% if post.category == "AI-Systems" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

---

## Trustworthy Intelligence
I develop intelligent systems for secure and trustworthy human-computer interaction. My work explores sensing-driven authentication, behavioral understanding, and privacy-aware perception, with applications in biometric security, gesture understanding, and robust user-facing intelligence.
{% for post in site.portfolio %}
  {% if post.category == "Security" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
