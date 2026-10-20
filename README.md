# Wildfire-Propagation-Modelling

**A GIS-based simulation of the 2003 Paradise Wildfire using Multicriteria Evaluation and Cellular Automata (MCE-CA)**

**Authors:** Alina Pharis and Varian Yu  
**Institution:** Simon Fraser University  
**Course:** GEOG 451 – Spatial Modelling  
**Date:** November 2024

## Project Overview
This project investigates the use of Multicriteria Evaluation and Cellular Automata (MCE-CA) to simulate wildfire propagation, using the 2003 Paradise Wildfire in California as a case study.

The model integrates geographic datasets representing topography, land cover, and human development to simulate wildfire spread over a 24-hour period.

The objective was to evaluate how effectively a cellular automata model could represent wildfire propagation and investigate the limitations of existing spatial modelling approaches.

## Methodology

The simulation combined spatial data processing, multicriteria evaluation, and cellular automata modelling.

### Spatial Data Preparation
- Processed digital elevation models (DEMs) to represent terrain characteristics.
- Reclassified land-use datasets to identify vegetation, urban development, and waterways.
- Standardized spatial datasets to a consistent raster resolution and geographic alignment.

### Multicriteria Evaluation
- Developed suitability maps incorporating slope and urban infrastructure.
- Applied weighted criteria to represent environmental influences on wildfire spread.
- Created constraint maps to restrict simulated fire propagation across waterways.

### Cellular Automata Simulation
- Simulated wildfire propagation using neighbourhood-based cell transition rules.
- Incorporated stochastic disturbance to represent unpredictable fire behaviour.
- Evaluated simulated wildfire progression against historical fire perimeter data.

## Results

The model reproduced several broad spatial patterns of wildfire propagation.

**Reported evaluation metrics:**
- **Overall accuracy:** 88.98%
- **Figure of Merit:** 0.8834

The results demonstrated the potential of MCE-CA approaches to simulate complex spatial processes while identifying limitations associated with simplified environmental variables, input data quality, and model parameters.


## Project Visualizations

### Final Simulation Compared to Actual Fire Spread

![Comparison of simulated and observed wildfire spread](figures/final-simulation.png)

### Wildfire Suitability Maps

![Multicriteria evaluation suitability maps](figures/suitability-maps.png)

## Full Research Paper

[Read the full wildfire modelling research paper](wildfire-modelling-report.pdf)


## Limitations and Future Research

The study identified several opportunities for further development:

- Integrating dynamic weather variables, including wind and humidity.
- Improving land-cover classification and model parameterization.
- Evaluating model performance across additional geographic regions and wildfire scenarios.
- Investigating hybrid approaches combining cellular automata with machine learning.

## Project Materials

The repository contains the research paper and selected figures illustrating the model methodology, simulation outputs, and evaluation.

This project was completed as undergraduate coursework at Simon Fraser University.
