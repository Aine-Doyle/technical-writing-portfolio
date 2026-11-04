---
layout: page
title: Projects
permalink: /projects/
lede: Documentation and UI content for IBM Data and AI products.
---

{% assign groups = site.projects | sort: "order" | group_by: "product" %}
{% for group in groups %}
## {{ group.name }}

{% include project-list.html projects=group.items %}
{% endfor %}
