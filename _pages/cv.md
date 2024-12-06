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
* M.S. in Computer Science, Cornell University, 2024
* B.A  in Mathematics and Computer Science (Magna Cum Laude), Cornell University, 2022

Research Experience
======
* Research Assistant @ Cornell University (September 2023-Present):
  * Designed and analyzed the first tractable stream-based selective sampling algorithm with provable guarantees when the problem is not realizable. Mentored two undergraduate students in their first research experience in machine learning. Working on manuscript on track for submission to ICML 2025
  * Developing a framework for constructing algorithms that achieve adaptive regret bounds for a general class of interactive decision-making problems. Recovered the small-loss bounds for contextual bandits via this framework. Ongoing work is in recovering variance aware bounds and other bounds via this framework. Project is on track for submission to COLT 2025.

* Undergraduate Research Assistant @ Cornell University (January 2021-February 2022):
  * Designed, implemented, and analyzed the results of experiments that tested the performance of basis reduction algorithms on bases for rotations of the integer lattice generated from a variety of basis sampling algorithms. Experiments were implemented in Python.
  * Designed, implemented, and analyzed the results of experiments that determined how heuristic sieving algorithms perform on the integer lattice. Experiments were implemented in C++.
  * Proved existence of orthogonal projection-based Cook reduction from ZSVP to 2-SVP.
  
Coursework
======
* 

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
  
Technical Skills
======
* Languages: Python, Java, C, C++, Mathematica, OCaml, MATLAB, SQL
* Technologies/Libraries: Github, Pytorch, Tensorflow, Jupyter
