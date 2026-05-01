# Spatial Working Memory Model with Gaussian Connectivity (Brian2)

## Overview
This project implements a spatially structured neural network demonstrating working memory–like dynamics. Neurons are arranged on a circular topology with distance-dependent synaptic connections.

## Model Description
- Leaky integrate-and-fire neurons  
- Ring topology (circular arrangement)  
- Gaussian local excitation (stronger nearby, weaker distant)  
- Global inhibitory component to stabilize activity  
- Localized external stimulus to initiate activity  

## Key Results
- Localized “bump” of neural activity forms in response to stimulus  
- Activity remains spatially confined due to Gaussian connectivity  
- Recurrent interactions sustain structured activity patterns  

## Interpretation
The model demonstrates attractor-like dynamics in a spatially organized network. Gaussian connectivity enables selective reinforcement of nearby neurons, producing stable, localized activity patterns similar to working memory representations.

## How to Run
```bash
pip install brian2 matplotlib
python spatial_working_memory_model.py
