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
* Ph.D in National University of Singapore, 2017 
	* Supervisor: Professor Weizhu BAO 
* B.S. in Peking University, 2012

Work experience
======
* 2017.01-2017.12: Research Assistant
  * Department of Mathematics, National University of Singapore
  * Supervisor: Professor Weizhu BAO

* 2018.01-2019.05: Postdoc
  * INRIA, Paris
  * Supervisor: Professor Benoit PERTHAME, Luis ALMEIDA

* 2019.06-2020.12: Postdoc
  * LJLL, Sorbonne University
  * Supervisor: Professor Benoit PERTHAME, Luis ALMEIDA

* 2021.02-2021.10: Postdoc
	* Department of Mathematics, Politecnico di Torino
	* Supervisor: Professor Tommaso LORENZI
  

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
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

