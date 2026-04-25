---
layout: archive
title: "Featured Projects"
permalink: /projects/
author_profile: true
---

---
layout: archive
title: "Featured Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

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
