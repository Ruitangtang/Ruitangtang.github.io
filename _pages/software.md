---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---

I develop research software for observation-constrained glacier modeling, Bayesian calibration, uncertainty quantification, and reproducible scientific computing.

## Coupled Frontal-Ablation Modeling Framework

My principal software contribution is a coupled framework integrating modified components of **OGGM**, **PyGEM**, and **SERMeQ**. It links models of climatic mass balance, 
glacier geometry, ice flow, and frontal ablation to support historical simulations and future projections of marine-terminating glaciers.

The framework combines multiple observational constraints with joint Bayesian calibration to estimate uncertain model parameters and propagate parameter uncertainty 
into historical simulations and future projections.

**Type:** Research software framework  
**My role:** Lead framework designer and developer  
**Application:** Historical simulations and projections for 71 marine-terminating glaciers in Svalbard  
**Scalability:** Designed for regional studies and extension to larger-scale glacier assessments  
**Programming languages:** Python and Shell  
**Status:** Public research release  
**Persistent DOI:** [10.5281/zenodo.18761729](https://doi.org/10.5281/zenodo.18761729)  
**Demo repository license:** MIT  
**Research archive license:** Creative Commons Attribution 4.0 International

## Core Capabilities

- Modular integration of modified **OGGM**, **PyGEM**, and **SERMeQ** components
- Climatic mass-balance and glacier-evolution modeling
- Ice-dynamics and frontal-ablation simulation
- Joint Bayesian calibration and parameter estimation
- Integration of multiple observational constraints
- Parameter and projection uncertainty quantification
- Historical simulation and scenario-based projection
- Configuration-driven experiment management
- Structured handling of model inputs and outputs
- Reproducible execution, documentation, and research archiving

## Technical Design

The framework is structured as a reproducible scientific software system rather than a single-purpose analysis script. Its implementation includes:

- A modular Python package
- YAML-based experiment configuration
- Python and shell workflow wrappers
- Ensemble-based Bayesian inference
- Multi-source model–observation integration
- Automated tests and validation checks
- Reproducible computational environments
- Versioned configurations and research outputs
- Documented workflows for review, reuse, and extension

## Regional Demonstration

The framework has been demonstrated and evaluated for **71 marine-terminating glaciers in Svalbard**, including historical simulations and projections through 2100.

The regional application tests the coupled architecture, jointly constrains surface mass-balance and frontal-ablation parameters, and evaluates how parameter uncertainty 
propagates into glacier projections. Although the current scientific evaluation is regional, the framework is built on globally applicable glacier-modeling systems and 
is designed for extension to other regions and larger-scale assessments.

## Access and Documentation

- **[Explore the workflow](https://github.com/Ruitangtang/frontal-ablation-glacier-demo)** — A lightweight, review-oriented demonstration containing the coupled architecture,
  Bayesian calibration workflow, configuration system, tests, documentation.
- **[Reproduce the research](https://doi.org/10.5281/zenodo.18761729)** — A citable software and research archive containing model code, configurations, computational environments,
  inputs, outputs, and reproducibility materials.
- **[Read the scientific study](https://doi.org/10.5194/egusphere-2026-1081)** — Framework design, calibration methodology, uncertainty analysis, and application to Svalbard glaciers.
- **[Access the published dataset](https://doi.org/10.11582/2026.7whvas95)** — Calibration, evaluation, parameter, and projection outputs for marine-terminating glaciers in Svalbard.
- **[Explore the research project](/projects/frontalablation-modeling/)** — Scientific motivation, framework development, regional demonstration, and key contributions.

## Development Principles

My software-development approach emphasizes:

- Transparent and modular architecture
- Reproducible computational environments
- Configuration-driven experiments
- Documented model inputs and outputs
- Testing and validation
- Persistent software citation and archiving
- Reusable code, workflows, and data products

## Citation and Reuse

The framework and associated research materials are available through the persistent Zenodo record:

[https://doi.org/10.5281/zenodo.18761729](https://doi.org/10.5281/zenodo.18761729)

Citation information, version history, licensing terms, and reproducibility instructions are provided in the Zenodo archive and GitHub repository. When reusing the framework or its outputs, 
please cite the archived research record together with the associated scientific publication.
