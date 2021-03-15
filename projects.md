---
layout: page
title: Projects
nav_order: 3
description: Outline of course project resources.
---

# Projects

Under construction.

{% assign data = site.modules | where: 'type', 'data' %}
{% for module in data %}
{{ module }}
{% endfor %}