---
permalink: /software/
title: "Software"
---


## PyEOGPR

PyEOGPR is a Python package for vegetation trait mapping using Gaussian Process Regression (GPR) on Earth observation cloud platforms like Google Earth Engine (GEE) and openEO. 

The package provides a variety of validated hybrid GPR models for common vegetation traits, as well as more challenging ones such as canopy nitrogen content (CNC), applicable to Sentinel-2 and Sentinel-3 data. Users can also incorporate newly trained GPR models for custom surface properties.

Key features:
- Probabilistic GPR models with associated uncertainty estimates for reliable retrievals  
- Large-scale vegetation analysis from local to global scales without local image downloads  
- Streamlined quantitative map generation with customizable time windows  
- Currently supports 27 generically applicable GPR models  
- Minimal coding expertise required  

PyEOGPR democratizes access to advanced GPR models in cloud environments, making spatial vegetation dynamics analyses accessible to a broad user base.

- [Documentation](https://pyeogpr.readthedocs.io/en/latest/index.html)
- [GitHub repository](https://github.com/daviddkovacs/pyeogpr)
- [Publication](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC12689493/)


## Google Earth Engine Application

A GEE web application for automated mapping of quantitative vegetation traits (e.g., LAI, fAPAR, GPP, chlorophyll/nitrogen/water content) from Sentinel-2 and Sentinel-3 imagery. 
The system operationalizes validated Gaussian Process Regression (GPR) models based on radiative transfer simulations in a fully cloud-based workflow. This enables on-demand generation of vegetation trait maps at 20–300 m resolution without requiring coding expertise.

Key innovations:
- Dynamic model loading for 30 GPR models enabling estimation of 11 vegetation traits  
- Automated masking and compositing for trait mapping  
- Savitzky-Golay smoothing for noise-reduced temporal analysis

The application demonstrates the potential of GEE to bridge advanced machine-learning retrieval methods and practical operational Earth observation use.

- [Repository](https://declerckemma.users.earthengine.app/view/gpr-vegetation-trait-retrieval)
