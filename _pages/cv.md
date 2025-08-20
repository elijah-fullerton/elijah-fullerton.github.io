---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. in Computer Science, Princeton University, 2031 (expected)
* B.A. in Information Science, Columbia University, 2023

Work experience
======
* June 2025 - August 2025: Research Scientist
  * Omen
  * Duties included: Developing ETL pipelines and database infrastructure. Designing customer profiling system and multi-agent ecosystem for automated securities trading.

* May 2023 - June 2025: Systems Engineer
  * Epic Systems
  * Duties included: Developing and managing ETL pipelines and database infrastructure.

{% comment %}
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

{% endcomment %}

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

{% comment %}
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams

{% endcomment %}
