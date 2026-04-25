---
layout: archive
title: "Featured Projects"
permalink: /projects/
author_profile: true
---

## Environmental Intelligence
I build physics-informed sensing systems for environmental intelligence using emerging modalities such as RF, metasurfaces, UWB radar, mmWave sensing, and multimodal learning. My work focuses on translating complex environmental signals into accessible and actionable information for real-world applications such as water quality monitoring, soil sensing, and intelligent agriculture.

{% for post in site.portfolio %}
  {% if post.category == "Environmental Intelligence" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

---

## AI-Systems
I design robust and efficient AI systems for multimodal sensing and real-world deployment. My research focuses on learning under missing, delayed, or heterogeneous modalities, with an emphasis on cross-modality inference, representation learning, and practical intelligence in resource-constrained environments.
{% for post in site.portfolio %}
  {% if post.category == "AI-Systems" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

---

## Cyber-Security

{% for post in site.portfolio %}
  {% if post.category == "Security" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
