---
layout: archive
title: 
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
{% assign education_data = site.data.education | sort: "year" %}
    {% for item in education_data %}
  {% include education.md %}
{% endfor %}

Service and Leadership
======
* Teaching Assistant
  * The University of British Columbia
  * Department: Chemical and Biological Engineering
  * Course: CHBE 474 Process Control Engineering
  * Time: Fall 2020

* Research Assistant
  * Summer 2018 - Fall 2019
    * The Tsinghua University
    * Department: Automation
    * Duties included: Causal discovery in Industrial process
    * Supervisor: Professor Fan Yang
  
  * Spring 2021 - Summer 2021
    * The Chinese University of Hong Kong, Shenzhen
    * Department: School of Data Science
    * Duties included: Missing value imputation, Causal discovery
    * Supervisor: Professor Jicong Fan
  
* Internship
  * Parkland Corporation
  * position: Data Scientist
  * Time: Fall 2019-Present

* Reviewing activities
  * IFAC World Congress 2020
  * American Control Conference 2021
  * Journal of The Franklin Institute
  * Engineering Applications of Artificial Intelligence
  * Industrial Engineering Chemistry Research

Awards and Honors
======
* Mitacs Accelerate Award
  * degree: Doctoral
  * institution: The University of British Columbia, Parkland Corporation
  * Time: 2019-Present
* President's Academic Excellence Initiative PhD Award
  * degree: Doctoral
  * institution: The University of British Columbia
  * Time: 2020-2021
* Faculty of Applied Science Graduate Award
  * degree: Doctoral
  * institution: The University of British Columbia
  * Time: 2019
* 2020 CHBE Awards in Breakthrough Innovations and Engineering Leadership
  * degree: Doctoral
  * institution: The University of British Columbia
  * Time: 2020
* Outstanding Graduate Student of Beijing
  * degree: Master's
  * institution: Beijing Education Bureau
  * Time: 2018
* National Scholarship for Graduates Student
  * degree: Master's
  * institution: Ministry of Education of the People's Republic of China
  * Time: 2016,2017
* Excellent Master Thesis of Beijing University of Chemical Technology
  * degree: Master's
  * institution: Beijing University of Chemical Technology
  * Time: 2018
* Outstanding Undergraduate Student of Beijing University of Chemical Technology
  * degree: Bachelor's
  * institution: Beijing University of Chemical Technology
  * Time: 2015

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
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>



