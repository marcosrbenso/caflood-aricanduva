# CAFLOOD Simulations – Aricanduva Catchment

This repository contains CAFLOOD simulations for the Aricanduva Catchment, located in the São Paulo Metropolitan Region, Southeastern Brazil.

[CAFLOOD](https://cafloodpro.com/) is a diffusive wave flood model based on cellular automata, designed to simulate flood dynamics at high spatial and temporal resolution.

The goal of this repository is to provide:

- Scripts for running CAFLOOD with different DEM sources and resolutions
- Input data processing workflows
- Parameter configurations for hydrodynamic simulations
- Outputs and visualizations of flood extents

```
📂 data/          # Input datasets (DEM, rainfall, river network, boundaries)
📂 scripts/       # R scripts for running CAFLOOD 
📂 results/       # Model outputs and analyses
📂 figures/       # Maps and plots of flood simulations
README.md         # Project description
```

# Getting Started
## Requirements

- Windows operating system
- R (≥ 4.2.0)
- Libraries: sf, terra, raster, tidyverse, ggplot2, cafloodr, etc.

## Caflodr

cafloodr is an R package to automate the preprocessing and execution of CADDIES/CAFLOOD using R. 



[![GitHub](https://img.shields.io/badge/GitHub-cafloodr-blue?logo=github)]([https://github.com/yourusername/yourrepository]([https://github.com/marcosrbenso/cam-413/blob/main/CAM_413_Aula_1_Introdu%C3%A7%C3%A3o_ao_R_no_Google_Colab.ipynb](https://github.com/marcosrbenso/cafloodr)))

# References

Guidolin, M., et al. (2016). A data-driven cellular automata model for flood simulation. Environmental Modelling & Software.

CAFLOOD GitHub repository: https://github.com/OpenHydroGroup/CAFlood
