---
layout: page
title: Outline
nav_order: 2
description: Listing of course modules and topics.
---

# Course Outline

Lectures marked with * will be given in class. Other lectures will be made available online as videos at the beginning of the week; students watch them before attending the corresponding class.

{% for module in site.modules %}
{{ module }}
{% endfor %}
