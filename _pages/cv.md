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
* Ph.D in Astrophysics, Vanderbilt University
* M.A. in Astrophysics, Vanderbilt University
* M.S. in Astronomy, San Francisco State University
* B.S. in Astronomy, Stony Brook University
* Nashville Software School Data Science Cohort 2

Work experience
======
* November 2020 to Present: Data Scientist II
* July 2019 to November 2020: Data Scientist
  * XSOLIS (Nashville, TN)
  * Work on a team of data scientists to develop and deploy machine learning models related to utilization management for healthcare facilities using clinical information.
    * Data extraction, cleaning, and analysis of both structured and unstructured data, including labs, vitals, orders, procedures, diagnoses, and large collections of documents
    * Build, validate, and deploy machine learning models, including linear and non-linear models, logistic and linear regression, and binary and multi-class targets
    * Model resource planning targets such as level of care, patient stratification, and discharge planning

* August 2014 to July 2019: Research Assistant
  * Vanderbilt University
  * Advisor: Professor Kelly Holley-Bockelmann
  * Computational astrophysics
    * Black hole seed formation and assembly in the first billion years of the Universe
  
Tools and Techniques
======
* Data analysis: Python/Pandas, R/Tidyverse
* Machine learning: scikit-learn, Keras, TensorFlow, XGBoost
* AWS Cloud Computing: EC2, ECS, S3
* Programming: Python, R, C/C++, SQL, BASH
* Workflow: git/Github, LaTeX, Markdown, VS Code, Jupyter Notebook

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