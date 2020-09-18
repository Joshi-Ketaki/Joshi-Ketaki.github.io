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
* Ph.D in Computer Science, Yale University, USA,           <emphasize> 2019-Present </emphasize>
* B.E. in Computer Engineering, University of Pune, India ,  <emphasize> 2011 - 2015  </emphasize>


Work experience
======
### Research Experience
* GCC Resource Center, Indian Institute of Technology, <strong> Advised by: </strong> Prof. Uday Khedker <emphasize> May 2014 - June 2015 </emphasize>
  * Worked on adding Inter procedural support from scratch in OptGen - a custom compiler optimization gen-erator for GCC - to create machine-independent optimizations based on simply the high level specificationsof the analyses.
  * Optimized the existing generator’s CFG node traversal to improve performance.

* Indian Institute of Tropical Meteorology, <strong> Advised by: </strong> Dr. Narendra Karmarkar <emphasize> February 2014 - June 2014 </emphasize>
  * Built  a  scalable  N-SAT  solver  for  data  extracted  from  meteorological  visualizations  to  aid  in  improving  theaccuracy of predictions.
  
* National Center for RadiAstrophysics / University of Pune ,  <strong> Advised by: </strong> Prof. Shubhangi Tikhe <emphasize> August 2013 - December 2013 </emphasize>
  * Presented a comparative study seminar on usage of different heterogeneous systems for pulsar de-dispersion.
  
### Industry Experience:
  * NVIDIA Graphics Pvt. Ltd. ,  <emphasize> January 2017- August 2019  </emphasize>
    * Improve utilization of the newly introduced ’Uniform Register File’ in the then upcoming GPU architecture-’Turing’.
    * Added compiler backend support for the newly introduced deep learning features for Turing architecture.  Ex-posed in CUDA 10.0 and CUDA 10.1.  (MMA etc.)  -Recognized as second Subject Matter Expert.
    * Added most of the encoding support for Turing solely-Recognized as Subject Matter Expert.
    * Redesigned the framework that creates encodable form of new instructions in the compiler backend as they getreleased by architecture.  -Recognized as Subject Matter Expert
  * Shoreline IoT  <emphasize> September 2016 - January 2017  </emphasize>
    * Worked on the organization’s first IoT product which was supposed to monitor boiler temperatures.
  * NVIDIA Graphics Pvt. Ltd <emphasize> June 2015 - August 2016 </emphasize>
    * Developed  a  novel  objective  algorithm  for  Fixed  Reference  Image  Analysis  for  images  rendered  across  GPU architectures Filed ISF for patent under NVIDIA.
    
  
Technical Skills
======
### Programming :
 C, C++, Python, MATLAB/Octave, OpenCV, NVPTX
### Compiler frameworks:
GCC, LLVM
### Debugging : 
 Valgrind
### Formal Verification tools
 Z3, Daphny, Coq
### Writing:
  Latex

  
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
