# SNN-CL Autonomous Driving Repository

## Overview
This repository contains the code and data generated during the realization of a Master's Final Project for the Master's Degree in Data Science at Universitat Oberta de Catalunya. The project focuses on the application of Spiking Neural Networks (SNNs) and Continual Learning (CL) in the context of autonomous driving.

**Title**: Application of Spiking Neural Networks and Continual Learning in Autonomous Driving\
**Author**: Sergio Costa Planells\
**Supervisor**: Raúl Parada Medina

## Repository Content
The repository is organized as follows:

### 1. `Notebooks`
Contains Jupyter notebooks for data preprocessing and definition, training and evaluation of models with CL implementations. Key files include:
- `DATA_PROCESSING.ipynb`: Exploration and preprocessing of datasets.
- `SNN_CL_TRAINING_EVAL.ipynd`: Definitions and architectures of the SNNs, CL implementations, training and evaluation of models in different experiments.
- `RESULTS.ipynb`: Integration of results.

### 2. `CL`
This directory includes the output data generated during the project. Each subfolder represents one experiment. Key files include:
- `Metrics.csv`: Contains metrics logged during training and evaluation of models.
- `emissions_{EXPERIMENT_NAME}.csv`: CodeCarbon emissions detailed log for equivalent CO2 emissions. 
- `hparams.yaml`: Relevant parameters used to train the model.
- `checkpoints/`: Folder containing best and last model checkpoints.

### 3. `environment.yaml`
A YAML file specifying the conda environment used for the project. This file includes all necessary dependencies.

### 4. `README.md`
This file, providing an overview of the repository.

## Usage
To reproduce the experiments or explore the code, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/scostap/SNN-CL-AutonomousDriving.git
   ```
2. Create the conda environment from the `environment.yaml` file:
   ```bash
   conda env create -f environment.yaml
   ```
3. Activate the environment:
   ```bash
   conda activate snn-cl-env
   ```
4. Navigate through the directories to explore code and data.




