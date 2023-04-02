# SILCS_AI_Permeability_2023
Combining SILCS and Artificial Intelligence for High-Throughput Prediction of Drug Molecule Passive Permeability Data

Poonam Pandey and Alexander D. MacKerell, Jr

Copyright (c) 2023, University of Maryland Baltimore All Rights Reserved

This release includes training and independent test dataset to create
a high-throughput predictive model for passive permeability of
drug-like molecules.The input feature vector used to train the
developed prediction model includes absolute free energies profiles of
ligands through a POPC-cholesterol bilayer based on ligand grid free
energy (LGFE) profiles obtained from the SILCS approach.

Contents:

the lgfe_perm_input_data_2023 subdirectory holds the feature vector
and target (logPm) for the training and independent test datasets.

hyperparameter_optimization.py file allows one to search hyper
parameters using grid search.

pred_logP.py file allows one to predict logPm values from training
model for random forest, GradientBoosting, LightGBM, and XGBoost
regression models.
