---
layout: archive
title: "Featured Projects"
permalink: /projects/
author_profile: true
---

## Environmental Intelligence

{% for post in site.portfolio %}
  {% if post.category == "Environmental Intelligence" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

---

## AI-Systems

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
