---
title: "Frontal-Ablation Modeling of Marine-Terminating Glaciers"
excerpt: "A coupled regional-to-global glacier-modeling framework, demonstrated in Svalbard using joint Bayesian calibration and multiple observational constraints."
collection: portfolio
permalink: /projects/frontalablation-modeling/
---

## Overview

This project develops an **open-source and reproducible framework** for modeling marine-terminating glaciers at regional-to-global scales. Built on the globally applicable **OGGM** and **PyGEM** modeling systems,
the framework integrates **SERMeQ** to represent climatic mass balance, glacier evolution, ice dynamics, and frontal ablation within a unified computational workflow. 
A central objective is to improve the representation of frontal ablation—ice loss through calving and submarine melting—which remains an important source of uncertainty 
in projections of marine-terminating glacier change. The framework uses joint Bayesian calibration to integrate multiple observational constraints, estimate key uncertain parameters, 
and propagate parameter uncertainty into historical simulations and future projections. 

## Regional Demonstration in Svalbard 
The framework was demonstrated and evaluated using **71 marine-terminating glaciers in Svalbard**, with historical simulations and projections through 2100. 
This regional application tests the coupled system, jointly constrains surface mass-balance and frontal-ablation parameters, and evaluates uncertainty in projected glacier evolution. 
Although demonstrated regionally, the framework is built on global glacier-modeling systems and is designed for extension to other regions and larger-scale applications.


## My Role

**Lead framework designer and developer**, responsible for model coupling, Bayesian calibration design, workflow implementation, uncertainty analysis, and reproducibility architecture.


## Key Contributions

- Led the design and development of an observation-constrained glacier-modeling and calibration framework.
- Created a scalable coupling architecture integrating **OGGM**, **PyGEM**, and **SERMeQ** within a reproducible workflow designed for regional-to-global applications.
- Developed a joint Bayesian calibration approach to estimate key surface mass-balance and frontal-ablation parameters from multiple observational constraints.
- Integrated glacier geometry, mass-balance, ice-dynamics, and frontal-ablation observations to support model calibration and evaluation.
- Quantified parameter uncertainty and propagated it into historical simulations and projections through 2100.
- Demonstrated and evaluated the framework for **71 marine-terminating glaciers in Svalbard**.
- Released citable software, model outputs, documentation, and reproducibility materials to support transparent research and future reuse.



## Key Result

The framework demonstrates how multiple observational constraints can jointly inform surface mass-balance and frontal-ablation parameters while propagating parameter uncertainty into glacier projections through 2100.



## Research Outputs 
- **[Research preprint](https://doi.org/10.5194/egusphere-2026-1081)** - Framework design, Bayesian calibration methodology, uncertainty analysis, and application to Svalbard.
- **[Software and research archive](https://doi.org/10.5281/zenodo.18761729)** - Citable model code, configurations, computational environment, inputs, outputs, and reproducibility materials.
- **[Published dataset](https://doi.org/10.11582/2026.7whvas95)** - Calibration, validation, parameter, and projection outputs for marine-terminating glaciers in Svalbard.
- **[Reproducible workflow demonstration](https://github.com/Ruitangtang/frontal-ablation-glacier-demo)** -A lightweight demonstration of the coupled modeling and Bayesian calibration workflow.

## Methods and Technical Capabilities 
- Process-based glacier modeling
- Coupled model integration
- Bayesian calibration and joint parameter estimation
- Multi-source observational data integration
- Uncertainty quantification
- Historical simulation and future projection
- Regional glacier-model execution
- Reproducible scientific software and workflow development

## Scientific Contribution
This project provides a scalable framework for integrating frontal ablation into large-scale glacier projections. 
By combining process-based models, observational constraints, and Bayesian calibration, it supports more physically 
consistent simulations of marine-terminating glaciers and more transparent assessment of projection uncertainty.
