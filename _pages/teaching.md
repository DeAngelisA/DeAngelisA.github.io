---
layout: single
title: "Teaching"
permalink: /teaching/
author_profile: true
---

The running list of my courses is available [at this link](https://docs.google.com/spreadsheets/d/1lgZFwmryGN5Bnr1jvxrEKB4W0sXWN26OH1xU_cDmWTQ/edit?usp=sharing) with *syllabi* and evaluations. 
I am happy to share teaching materials upon request.  

Recently I was invited to give a lecture on "Algorithms and Democracy" at the [Lecture Series on Digital Transformation](https://www.unilu.ch/fileadmin/user_upload/Ringvorlesung_Digitalisierung_Programm.pdf) of the University of Lucerne. In my lecture I discussed some digital transformation trends and presented some results from my ongoing research. The slides [are available here](https://deangelisa.github.io/files/deangelis-algorithms-democracy.pdf). 

{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
