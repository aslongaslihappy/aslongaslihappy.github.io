---
layout: archive
title: "CV"
permalink: /cv/
description: "李天恩的研究方向、论文成果与开源项目。"
author_profile: true
redirect_from:
  - /resume/
---

## Research Profile

Researcher working on multi-objective optimization, evolutionary computation, deep reinforcement learning and operations research, with applications in flexible job shop scheduling, automated guided vehicles and large-language-model-assisted algorithm design.

## Research Interests

- Multi-objective Optimization
- Computational Intelligence and Evolutionary Optimization
- Deep Reinforcement Learning
- Flexible Job Shop Scheduling and AGV Scheduling
- Automated Algorithm Design with Large Language Models
- Operations Research

## Publications

<ol class="cv-publications">
{% for post in site.publications reversed %}
  <li>{{ post.citation }} <a href="{{ post.paperurl }}">DOI</a></li>
{% endfor %}
</ol>

## Open-source Projects

{% for post in site.portfolio %}
- [{{ post.title }}]({{ post.repo_url }}) — {{ post.summary }}
{% endfor %}

> Education, appointments, awards and academic service can be added once the information is ready for publication.

