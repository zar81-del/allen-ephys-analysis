# Allen Ephys Analysis


Electrophysiological analysis of neuronal cell types using the Allen Cell Types Database.


## Motivation

Exploring cell-type-specific electrophysiological signatures, with an interest in
methods that transfer to synaptic physiology work — event detection, current-voltage
relationships, and appropriate handling of nested data structures.

## Repository structure


Data and figures are excluded from version control — see `.gitignore`. Everything
in `data/processed/` and `figures/` can be regenerated from raw data and the code
in this repository.

## Status

In progress. Environment setup and analysis pipeline to follow.

## Setup

Clone the repository and create the environment:

    git clone https://github.com/zar81-del/allen-ephys-analysis.git
    cd allen-ephys-analysis
    conda env create -f environment.yml
    conda activate ephys