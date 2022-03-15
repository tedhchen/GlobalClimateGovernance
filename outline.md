---
layout: page
title: Outline
nav_order: 2
description: Listing of course modules and topics.
---

# Course Outline

Required readings should be completed before the corresponding class; they are designed to facilitate your understanding of the lectures or to help you with your group work. Additional materials are recommended but optional.

**As we deal with the difficulties of online learning during a pandemic, the course outline is subject to change, but never in the direction of increased difficulty.**

{% assign outline = site.modules | where: 'type', 'outline' %}
{% for module in outline %}
{{ module }}
{% endfor %}