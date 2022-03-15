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
This course is centered around a research project that students will complete in groups of approximately 3-4. We conceive of research broadly, to include academic work from multiple disciplines (e.g. traditional disciplinary social science, climate science, computational social science) as well as policy-oriented research in the vein of something produced by NGOs or international organizations.

Throughout the course, students will produce three outputs:
- a written interim report that outlines the topic, motivation, protocols, and expected findings (due 8.4)
- an oral presentation based on all progress made by the end of the lecture portion of this course, ideally including initial results (due in class on 21.4)
- a final written report in a format agreed-upon between the group and the instructors (see below for more details; due 6.5)

### Logistics
The target group composition is 3-4 students. However, adjustments are probably necessary depending on exact enrollment. To facilitate groups that make sense both in terms of common interests and balanced skill sets, instructors will send a short survey for students to answer.

### Format
The suggested formats for the final written report are short academic "research notes" or papers for computational social science conferences. These will generally be approximately 3000-4000 words in length. We suggest these formats because they should be more manageable for students and as academic researchers, we can provide the most help. Groups that want to produce other kinds of written reports (e.g. NGO-type policy briefs, longer academic research papers) are more than welcome to do so, but should consult the instructors first to ensure feasbility.

Examples [format requirements]:
- **[[Letter](https://www.cambridge.org/core/journals/american-political-science-review/information/instructions-contributors)]** Hazlett, C., Mildenberger, M. 2020. ["Wildfire Exposure Increases Pro-Environment Voting within Democratic but Not Republican Areas."](https://doi.org/10.1017/S0003055420000441){:target="_blank"} _American Political Science Review_ 114(4): 1359-1365.
- **[[Article](https://publishingsupport.iopscience.iop.org/journals/environmental-research-letters/about-environmental-research-letters/#article-types)]** Chen, T.H.Y., Lee, B. 2022. ["Income-based inequality in post-disaster migration is lower in high resilience areas: Evidence from U.S. internal migration"](https://doi.org/10.1088/1748-9326/ac5692){:target="_blank"} _Environmental Research Letters_ 17: 034043.
- **[[Brief report](https://www.tandfonline.com/action/authorSubmission?show=instructions&journalCode=fenp20&#prep)]** Michelson M.R., DeMora, S.L. ["Making activists out of environmentalists: New experimental evidence"](https://doi.org/10.1080/09644016.2021.1915013){:target="_blank"} _Environmental Politics_ 31(1), 173-181.

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
