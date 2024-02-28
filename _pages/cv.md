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
<!---* M.S. in Jekyll, GitHub University, 2014 --->
* B.S. in Computing, Queen's University, 2023

Work experience
======
* Research Assistant
  * Queen's University
  <!---* Duties included: Merging pull requests --->
  * 2023-Present
  * Supervisor: Professor Steven Ding

* Software Developer
  * Synapse Mobile Networks
  * 2023

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>