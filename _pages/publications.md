---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

My research spans glacier modeling, data assimilation, glacier dynamics, satellite remote sensing, and interdisciplinary Earth-system science. Publications are organized by research theme and listed in reverse chronological order.

For citation metrics and the complete external record, visit my [Google Scholar profile](https://scholar.google.com/citations?user=P7UUU4kAAAAJ&hl=en).

{% include base_path %}

## Glacier Modeling, Data Assimilation, and Uncertainty

Research on coupled glacier modeling, frontal ablation, Bayesian calibration, cryospheric data assimilation, and uncertainty-aware projection.

{% assign modeling_publications = site.publications
  | where: "category", "glacier-modeling"
  | sort: "date"
  | reverse %}

{% for post in modeling_publications %}
  {% include archive-single.html %}
{% endfor %}

## Glacier Observation, Dynamics, and Remote Sensing

Research combining satellite observations, field measurements, and model-derived data to investigate glacier area, mass, elevation, surface motion, hydrology, and downstream impacts.

{% assign observation_publications = site.publications
  | where: "category", "glacier-observation"
  | sort: "date"
  | reverse %}

{% for post in observation_publications %}
  {% include archive-single.html %}
{% endfor %}

## Interdisciplinary Earth-System Modeling

Research applying regional environmental models to atmospheric composition, climate interactions, and related Earth-system processes.

{% assign earth_system_publications = site.publications
  | where: "category", "earth-system-modeling"
  | sort: "date"
  | reverse %}

{% for post in earth_system_publications %}
  {% include archive-single.html %}
{% endfor %}
