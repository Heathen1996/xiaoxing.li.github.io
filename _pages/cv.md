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
* Ph.D in Mechanical Engineering, Eindhoven University of Technology
* M.S. in Power Engineering and Engineering Thermophysics, Shanghai Jiao Tong University, 2018
* B.S. in Energy and Power Engineering, Central South University, 2014
  
Skills
======
* Coding in C++.
* Making figures by MATLAB and Origin.

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
