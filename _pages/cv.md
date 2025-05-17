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
=========

* Dipl.-Ing. in Renewable Energy Systems, Dresden University of Technology, 2021

Work experience
===============

* 2021 - 2025: Research Associate

  * Dresden University of Technology
  * Duties includes: Updates and improvements to template

Publications
============

<ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
=====

<ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
========

<ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Service and leadership
======================

* Currently signed in to 43 different slack teams
