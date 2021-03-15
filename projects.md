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
Topics for the research projects can be, within reason, anything related to climate governance, broadly defined as the social and political drivers and consequences of policies associated with the distributional outcomes stemming from climate change. Simply to make sure the topics are feasible, selected topics have to be approved by the instructors.

Here are some possible topics:
- **Policy cooperation:** What determines cooperation between policy actors? How are coalitions or oppositions formed within a policy system? What is the relationship between patterns of policy collaboration and implementation of climate policies?
- **Climate communication:** How do groups or individuals communicate about climate change? What are effective forms of climate communication? How to antagonist groups communicate their opposition? What kind of misinformation is there?
- **Public opinion:** Who cares about what of climate change, when and where? Why?
- **Role of science:** How does "science" shape the social and political aspects of climate governance? What is the evolution of scientific communication on climate change?
- **Social movements:** What drives or inhibits climate activism? What is the relationship between new technologies and climate social movements?
- **Social and political consequences of climate change:** How do individuals respond to changes in their lives that resulted from climate change?


## Possible Data Sources
Here are some possible data sets that groups can use for their research projects. Each data set has a brief description, as well as tags for which broad category of topics they can be used for. Students are welcome to identify and collect their own data, but consultation with the instructors is recommended.

{% assign data = site.modules | where: 'type', 'data' %}
{% for module in data %}
{{ module }}
{% endfor %}