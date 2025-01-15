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
* Ph.D in Advanced Mechanical Engineering, University of Sheffield, 01/2025 (expected)
* M.S. in Advanced Mechanical Engineering, University of Sheffield, 09/2019-09/2020
* B.S. in Mechanical Engineering, University of the West of Scotland, 09/2018-06/2019
* B.S. in Mechanical Design and Automation, Changchun institute of technology, 09/2015-06/2019

Research experience
======
PhD Research
- Worked and associated with the AMRC for addressing TFP-induced manufacturing defects.
- Tools and Methods:
  * Multiscale characterisation of TFP composite from microscale to mesoscale using SEM and X-ray Microscope (Zeiss Versa 620). In-situ characterisation of TFP composite using Deben CT5000 loading rig.
  * Generating Representative Volume Element (RVE) model based on the characterised fibre distribution behaviour using Python to achieve high fibre volume fraction and periodicity.
  * Constructing mesoscopic model using SolidWorks and achieving automated model construction process using Python/PyQt.
  * Determination of failure mechanism of TFP-composites and developing damage criterion on the strength prediction of TFP composites through VUMAT/UMAT subroutine and ABAQUS simulation.
  * Developing Python/C++ based DVC algorithm to produce volumetric strain results from temporal CT results to validate numerical models.
  
Skills
======
* Programming: Python, C/C++, MATLAB, FORTRAN, VB.NET
* Software: ABAQUS, ANSYS, SOLIDWORKS, Fusion 360, Dragonfly ORS.
* Experiment: ZEISS Veras 620 X-ray Microscope, Deben CT5000 loading rig,
  2D/3D DIC.
* Others: Literature sorting and classification; Sample preparation; Rig design; Data analysis; Scientific graph plotting.

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
  
Service and leadership
======
* Currently signed in to 43 different slack teams
