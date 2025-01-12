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
* M. Tech. in Climate Science, Indian Institute of Science, 2016
* B. Tech. in Chemical Engineering, Pondicherry Engineering College, 2014

Work experience
======
* Present: Manager - Energy Anlytics and Forecasting, AGEL
  * Responsible for developing and maintaining renewable energy forecasting solution for 12GW portfolio under.
  * Leading a team of data scientist, meteorologist and python developer to innovate different energy forecasting products executing end-to-end software development cycle
  * Responsible to conduct PoCs with various Indian and global forecasting agencies to evaluate their performance, on-board them and combining them for most profitable business solution
  * Bridging the gap between multiple stakeholders, from desk meteorologist to CXOs, to make the innovation and operation run hand-in-hand
  * Building next-generation weather-cum-energy forecasting solution combining AI and WRF to generate forecast ensemble for upto 48 hours lookahead time

* Nov 2023: Data Engineer, Tomorrow.io
  * Built AI and physics-based solution to reduce bias from various regional and global weather models.
  * Created an customers-centric intelligence platform to analyse forecast quality of both in-house and third-party weather models.
  * Designed unsupervised and supervised models for signal error detection.
  * Created ETL pipelines and developed database to capture and store various weather datasets including AWS, model, radar and satellite.
  * Led PoC for ETL vendor selection, helped management for procurement.

* Apr 2021: Senior meterologist, Vestas
  * Built ML and AI models to improve weather forecasting accuracy based on national energy trading regulations for both short and medium term window.
  * Built and deployed hyper-local ML-NWP-ensemble weather prediction models for rainfall, GHI, wind-speed, temperature and moisture content.
  * Set up a weather analysis and visualisation platform for wind and solar farms spread across four continents.
  * Developed methodologies for long-term wind power assessment combining ML and climatology from multiple global models.
  * Automated wind-turbine power-curve construction using millions of data points for accurate plant-specific wind-speed-to-power conversion


* Jul 2019: Software Engineer, Parabole.ai
  * Built a framework to extract terms and phrases from large scale corpus (>10k docs) using Solr and python-dask.
  * Developed a graph-based unsupervised document summariser for Cyber Security and Operational Risk domain.
  * Worked on various aspects of ontology generation including dependency-tree, Z-score, and property mapping of text using open-source datasets like Wikipedia and Twitter feeds.

* Aug 2018: Research Engineer, CSTEP
  * Set-up and optimise high resolution (1km) weather and air-pollution modelling and forecasting system for Bengaluru city using WRF-CAMx.
  * Build and set-up CAMx modelling system, estimated the impact of emission from upcoming thermal power plant on Indian Air Quality.
  * Built weather and economy based short and long-term demand load prediction model using ML (nMAE < 5%), used for Karnataka State.
  * Generated consumers-specific consumption pattern from feeder-level data using clustering. 
  
  
Skills
======
* python
  * pytorch
  * scikit-learn
  * dask
  * matplotlib
  * Xarray 

* SQL and ETL
  * PostgreSQL
  * cloudSQL
  * Xplenty
  * matillion
  
* Weather and air quality
  * WRF
  * FourCastNet 
  * CAMx
  * flexpart

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul> -->
<!--   
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams -->
