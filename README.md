# Submesoscale-Informed-Modeling

This repository contains the neural network architecture, training workflow, and reproducibility materials associated with the manuscript:

“A high-fidelity dynamic downscaling framework with submesoscale-informed neural network,” submitted to the Journal of Advances in Modeling Earth Systems.

The exact version of the code used to generate the results in the manuscript is permanently archived on Zenodo: https://doi.org/10.5281/zenodo.18780159

## Demo mode
The notebooks run in DEMO_MODE=True so they can execute without the full high-resolution simulation datasets. Dummy tensors are used to demonstrate the model architecture and inference workflow.

For reproducibility purposes, trained model weights, example input/output data, and figure reproduction scripts are provided in the Zenodo archive.

## Data availability
The HYCOM GLBy0.08 reanalysis data used as boundary and initial conditions are publicly available from the HYCOM data server (https://www.hycom.org). The materials necessary to reproduce the figures and statistical analyses presented in the manuscript are included in the Zenodo archive linked above. Full high-resolution simulation outputs are not distributed but can be regenerated using the archived code and publicly available input data.
