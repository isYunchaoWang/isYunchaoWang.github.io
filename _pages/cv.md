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
* Ph.D in in Computer Science and Technology, College of Computer Science and Technology (College of Software), Zhejiang University of Technology, 2025 (expected)
* M.S. in in Control Science and Engineering, College of Information Engineering, Zhejiang University of Technology, 2020
* B.S. in Electronic Science and Technology, College of Information Engineering, Zhejiang University of Technology, 2016

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>


