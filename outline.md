---
layout: page
title: Outline
nav_order: 2
description: Listing of course modules and topics.
---

# Course Outline

Lectures marked with * will be given in class. Other lectures will be made available online as videos at the beginning of the week; students shold watch them before attending the corresponding class.

Required readings should be completed before the corresponding class; they are designed to facilitate your understanding of the lectures or to help you with your group work. Additional materials are recommended but optional.

**As we deal with the difficulties of online learning during a pandemic, the course outline is subject to change, but never in the direction of increased difficulty.**

{% assign outline = site.modules | where: 'type', 'outline' %}
{% for module in outline %}
{{ module }}
{% endfor %}