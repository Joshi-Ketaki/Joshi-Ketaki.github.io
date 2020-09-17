---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Research
======
The Computer Architecture stack in today's systems is becoming more heterogenous than ever. Today's systems cater to safety-critical or real-time applications more often making high throughput, increased system utilization, reliability and security a necessity rather than a feature. Asynchronous interfaces in form of asynchronous system services or micro-services help achieve the goal of increased system utilization and throughput. Formalizing the non-intuitive asynchronous model makes it achievable for safety-critical applications as well as eases programming complexity in any application. Hence, I am looking at formalizing the asynchronous programming interface to make it easy to reason about in terms of programmability, safety and correctness.


Education
======
* Ph.D in Computer Science, Yale University, USA,           2019-Present
* B.E. in Computer Engineering, University of Pune, India , 2015


Work experience
======
  * Nvidia Graphics Pvt. Ltd. , January 2017- August 2019
    * Improve utilization of the newly introduced ’Uniform Register File’ in the then upcoming GPU architecture-’Turing’.
    * Added compiler backend support for the newly introduced deep learning features for Turing architecture.  Ex-posed in CUDA 10.0 and CUDA 10.1.  (MMA etc.)  -Recognized as second Subject Matter Expert.
    * Added most of the encoding support for Turing solely-Recognized as Subject Matter Expert.
    * Redesigned the framework that creates encodable form of new instructions in the compiler backend as they getreleased by architecture.  -Recognized as Subject Matter Expert
  
Technical Skills
======
* C
* C++
* Python
* Valgrind
* Z3
* Daphny
* Coq
* Latex

  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
