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

Professional Experience
======
* **XSOLIS** (Nashville, TN)
  * *Data Scientist II*: November 2020 to Present
  * *Data Scientist*: July 2019 to November 2020
    * **Machine Learning**: Modeled resource planning targets for healthcare facilities: level of care, patient stratification, and discharge planning.  Built, tuned validated, and characterized machine learning models and deep learning networks to predict binary, multi-class, and regression targets.
    * **Natural Language Processing**: Created topic representations of collections of documents for use in predictive models.  Piloted techniques to advanded team-wide efforts to efficiently tune topic models.}
    * **Data Wrangling and Analysis**: Gathered, cleaned, and analyzed structured and unstructured data, including: labs, vitals, orders, procedures, diagnoses, and large collections of documents.  Developed and implemented methods for out-of-core computation while processing big data and training networks.
    * **Application Deployment**: Deployed machine learning models to run on AWS EC2 instances as Flask applications within Docker containers.  Architected serverless application workflow for a prediction explanation service.
    * **Engagement**: Communicated with company stakeholders and subject matter experts to define objectives and develop requirements.  Provided company-wide education on the data science process for non-scientists via a Lunch-and-Learn series.  Presented work at the 2020 Nashville Analytics Summit.

* **Vanderbilt University** (Nashville, TN)
  * *Research Assistant*: August 2014 to July 2019
    * **Computational Astrophysics**: Applied C/C++ N-body smooth particle hydrodynamics cosmological simulations to study the conditions of black hole formation and black hole demographics in the first billion years of the Universe.  Developed a computational model for black hole seed formation, and integrated this model into the cosmological simulation Gasoline.  Adapted a semi-analytic model for black hole assembly from literature to a custom-built Python program that tracked the evolution of black hole seeds after the end of our simulations.  Published two peer-reviewed articles in The Astrophysical Journal, presented work at national and international conferences, and contributed annually to the writing of academic grant applications.
    * **High-performance Computing**: Awarded 730,500 computing hours on the national supercomputing network XSEDE TACC/Stampede through a competitive grant process (\$33,140 equivalent).  Deployed cosmological simulations in high-performance computing environments.  Interned at Lawrence Livermore National Lab (Summer 2016), and wrote a smooth particle hydrodynamics kernel solver for the simulation Cosmos++.  Attended the International High Performance Computing Summer School in Ljubljana, Slovenia (Summer 2016), a one-week intensive focusing on state-of-the-art simulation techniques.
  * *Teaching Assistant*: August 2014 to May 2017
    * **Teaching**: Led one section per semester of the laboratory component of Vanderbilt’s undergraduate-level introductory astronomy course.  This course covered topics including celestial motion, spectroscopy, extrasolar planet detection, stellar photometry, basic telescope operation, and night sky observation.
  
Tools and Techniques
======
* __Workflow__: git/Github, Jira, Confluence, VS Code, Jupyter Notebook, LaTeX, Markdown
* __Application Deployment__: Boto3, Docker, EC2, ECS, ECR, S3, Lambda, SNS, SQS
* __Operating systems__: Mac OS, Windows, Linux (Amazon Linux, CentOS, Red Hat)
* __Machine Learning Libraries__: scikit-learn, Keras, TensorFlow, XGBoost
* __Programming Languages__: Python, R, C, C++, SQL, Bash
* __Web APIs__: Flask, Waitress

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