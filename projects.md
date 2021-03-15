---
layout: page
title: Projects
nav_order: 3
description: Outline of course project resources.
---

# Projects
{:.no_toc}

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## Description
This course is centered around a research project that students will complete in groups of approximately 4-5. We conceive of research broadly, to include academic work from multiple disciplines (e.g. traditional disciplinary social science, climate science, computational social science) as well as policy-oriented research in the vein of something produced by NGOs or international organizations.

Throughout the course, students will produce three outputs:
- an written interim report that outlines the topic, motivation, protocols, and expected findings
- an oral presentation based on all progress made by the end of the lecture portion of this course, ideally including initial results
- a final written report in a format agreed-upon between the group and the instructors (see below for more details)

### Logistics
The target group composition is 3-4 University of Helsinki students and 1-2 Aalto University students in each group. However, adjustments are probably necessary depending on exact enrollment. To facilitate groups that make sense both in terms of common interests and balanced skill sets, instructors will send a short survey for students to answer.

### Format
The suggested formats for the final written report are short academic "research notes" or papers for computational social science conferences. These will generally be approximately 3000-4000 words in length. We suggest these formats because they should be more manageable for students and as academic researchers, we can provide the most help. Groups that want to produce other kinds of written reports (e.g. NGO-type policy briefs, longer academic research papers) are in principle welcome to do so, but should consult the instructors first to ensure feasbility.

## Potential Topics

## Possible Data Sources
{% assign data = site.modules | where: 'type', 'data' %}
{% for module in data %}
{{ module }}
{% endfor %}